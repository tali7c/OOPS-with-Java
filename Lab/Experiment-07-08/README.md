# Experiment-07&08 — Class Design and Object Creation + Method Overloading and Constructors

This lab sheet combines **Experiment-07** and **Experiment-08** as per the lab syllabus.

## General instructions (lab manual)

- Write and execute programs independently.
- Follow standard Java coding conventions.
- Submission must include: **source code**, **output**, and brief **observations**.

## Experiment 07 (Syllabus)

**Objective:** To understand classes, objects, and constructors.  
**Problem Statement:** Design classes with data members and member functions.  
**Expected Outcome:** Students will understand object creation and encapsulation.

## Experiment 08 (Syllabus)

**Objective:** To demonstrate compile-time polymorphism.  
**Problem Statement:** Implement method and constructor overloading in Java.  
**Expected Outcome:** Students will understand method resolution at compile time.

## Lab tasks (recommended scenario)

### Task A — Student class with validation (Exp-07)

Create `StudentDemo.java` with a `Student` class:

Fields (private):
- `rollNo` (must be positive)
- `name` (must be non-empty)
- `cgpa` (0..10)

Requirements:
- validate in constructor
- provide a safe update method `updateCgpa(double)` with validation
- print objects using `toString()`

### Task B — Overloading demo (Exp-08)

Create `OverloadingDemo.java`:

1) Create class `Box` with overloaded constructors:
- default: unit box
- 1 parameter: cube
- 3 parameters: `w, h, d`

2) Add method `volume()`.

3) Write overloaded methods:
- `area(double r)` → circle area
- `area(double w, double h)` → rectangle area

4) In `main`, create objects with different constructors and print volumes and areas.

## Deliverables

- `StudentDemo.java`
- `OverloadingDemo.java`
- Sample run/output for both programs
- Observations (5–10 lines): why constructors help initialization; how Java chooses the correct overloaded method

## Optional extensions

- Add a copy constructor to `Box` (constructor overloading practice).
- Add validation in `Box` so dimensions cannot be negative.
