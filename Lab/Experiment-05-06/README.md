# Experiment-05&06 — Arrays and Multidimensional Arrays + String Handling

This lab sheet combines **Experiment-05** and **Experiment-06** as per the lab syllabus.

## General instructions (lab manual)

- Write and execute programs independently.
- Follow standard Java coding conventions.
- Submission must include: **source code**, **output**, and brief **observations**.

## Experiment 05 (Syllabus)

**Objective:** To work with one-dimensional and two-dimensional arrays.  
**Problem Statement:** Develop Java programs to perform operations on arrays.  
**Expected Outcome:** Students will be able to store and process data using arrays.

## Experiment 06 (Syllabus)

**Objective:** To perform string manipulation using Java String classes.  
**Problem Statement:** Implement string operations using built-in Java methods.  
**Expected Outcome:** Students will be able to manipulate textual data.

## Lab tasks (recommended scenario)

### Task A — Array operations (Exp-05)

Create `MarksAnalysis.java`:

1) Read `n`.
2) Read `n` marks into an `int[]`.
3) Print:
- min, max, sum, average
- passCount (marks >= 40)

Create `MatrixAdd.java`:

1) Read rows `r` and cols `c`.
2) Read matrix A and matrix B (same size).
3) Print the matrix sum `A + B`.

### Task B — String toolkit + palindrome (Exp-06)

Create `StringToolkitDemo.java` and demonstrate:

1) `==` vs `equals()` for:
- `new String("upes")`
- string literals like `"java"`

2) Immutability:
- show that calling `toUpperCase()` does not change the original string unless stored

3) Palindrome checker:
- read a full line
- ignore spaces and case
- print whether it is a palindrome

## Deliverables

- `MarksAnalysis.java`
- `MatrixAdd.java`
- `StringToolkitDemo.java`
- Sample run/output for all programs
- Observations (5–10 lines): `==` vs `equals()`; why `String` is immutable; when to use `StringBuilder`

## Optional extensions

- Add matrix transpose as an extra program.
- Extend palindrome checker to ignore punctuation (like `, . ! ?`).
