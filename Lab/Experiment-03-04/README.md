# Experiment-03&04 — Data Types, Variables, and Operators + Decision Making and Looping Constructs

This lab sheet combines **Experiment-03** and **Experiment-04** as per the lab syllabus.

## General instructions (lab manual)

- Write and execute programs independently.
- Follow standard Java coding conventions.
- Submission must include: **source code**, **output**, and brief **observations**.

## Experiment 03 (Syllabus)

**Objective:** To apply data types and operators in Java programs.  
**Problem Statement:** Write a Java program demonstrating the use of primitive data types and operators.  
**Expected Outcome:** Students will understand data manipulation using operators.

## Experiment 04 (Syllabus)

**Objective:** To implement control flow using conditional and looping statements.  
**Problem Statement:** Design a Java program using decision-making and looping constructs.  
**Expected Outcome:** Students will be able to control program flow effectively.

## Lab tasks (recommended scenario)

### Task A — Types + operators mini-lab (Exp-03)

Create `TypesOperatorsDemo.java`:

1) Read two integers `a` and `b`.
2) Print:
- `a + b`, `a - b`, `a * b`
- if `b != 0`: integer division `a / b`, floating division `a / (double) b`, remainder `a % b`
3) Demonstrate precedence:
- `2 + 3 * 4`
- `(2 + 3) * 4`
4) Demonstrate casting:
- widening: `int -> double`
- narrowing: `double -> int` (show truncation)
5) Print a boolean expression using `&&` and `||` (any simple example).

### Task B — Menu-driven utility program (Exp-04)

Create `MenuUtility.java` that repeats until Exit:

1) Even/Odd check  
2) Factorial (loop)  
3) Prime check  
4) Exit  

Requirements:
- Use `switch` for menu choice handling.
- Use loops for factorial and prime check.
- Handle invalid menu choice.
- Show at least one `continue` usage (example: skip processing if input is negative).

## Deliverables

- `TypesOperatorsDemo.java`
- `MenuUtility.java`
- Sample run/output for both programs
- Observations (5–10 lines): integer vs floating division; why we check `b != 0`; where loops are used

## Optional extensions

- Add a menu option: sum of digits of a number.
- Print multiplication table of a number using a loop.
