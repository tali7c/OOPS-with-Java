# Experiment-09&10 — Inheritance and Method Overriding + Abstract Classes and Interfaces

This lab sheet combines **Experiment-09** and **Experiment-10** as per the lab syllabus.

## General instructions (lab manual)

- Write and execute programs independently.
- Follow standard Java coding conventions.
- Submission must include: **source code**, **output**, and brief **observations**.

## Experiment 09 (Syllabus)

**Objective:** To implement inheritance and runtime polymorphism.  
**Problem Statement:** Create base and derived classes demonstrating inheritance.  
**Expected Outcome:** Students will understand code reusability.

## Experiment 10 (Syllabus)

**Objective:** To implement abstraction using abstract classes and interfaces.  
**Problem Statement:** Design programs using abstract classes and interfaces.  
**Expected Outcome:** Students will understand abstraction and multiple inheritance.

## Lab tasks (recommended scenario)

### Task A — Inheritance + overriding (Exp-09)

Create `InheritanceDemo.java`:

1) Create base class `Employee` with:
- fields: `id`, `name`
- method: `double calculatePay()` (default/base behavior)

2) Create derived classes:
- `SalariedEmployee extends Employee` (monthly salary)
- `ContractEmployee extends Employee` (hourlyRate × hours)

3) Override `calculatePay()` in both derived classes and use `@Override`.

4) Demonstrate runtime polymorphism:
- store mixed objects in an `Employee[]`
- call `calculatePay()` in a loop and print results

### Task B — Abstract class + interface (Exp-10)

Create `AbstractInterfaceDemo.java`:

**Part 1 — Abstract class**

1) Create abstract class `EmployeeBase`:
- common fields like `name`
- abstract method `double calculateSalary()`
- (optional) concrete helper method like `printPayslip()`

2) Create subclasses `FullTimeEmployee` and `InternEmployee` that implement salary logic.

**Part 2 — Interface**

1) Create interface `Payable` with method `double amountDue()`.
2) Implement in:
- `Invoice`
- `SalarySlip`
3) Store both in a `Payable[]` and compute total due.

## Deliverables

- `InheritanceDemo.java`
- `AbstractInterfaceDemo.java` (single-file demo is OK)
- Sample run/output for both programs
- Observations (5–10 lines): overriding + dynamic dispatch; when you prefer interface vs abstract class

## Optional extensions

- Add a `default` method in an interface and call it from an implementation.
- Add input validation (negative hours/salary should be rejected).
