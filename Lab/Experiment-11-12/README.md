# Experiment-11&12 — Exception Handling + Multithreading

This lab sheet combines **Experiment-11** and **Experiment-12** as per the lab syllabus.

## General instructions (lab manual)

- Write and execute programs independently.
- Follow standard Java coding conventions.
- Submission must include: **source code**, **output**, and brief **observations**.

## Experiment 11 (Syllabus)

**Objective:** To handle runtime errors using exception handling mechanisms.  
**Problem Statement:** Develop programs using try-catch-finally blocks.  
**Expected Outcome:** Students will write robust programs.

## Experiment 12 (Syllabus)

**Objective:** To implement multithreading in Java.  
**Problem Statement:** Create threads using Thread class and Runnable interface.  
**Expected Outcome:** Students will understand concurrent programming.

## Lab tasks (recommended scenario)

### Task A — Exception handling (Exp-11)

Create `ExceptionHandlingDemo.java`:

**Part 1 — Safe division with `finally`**

1) Read integers `a` and `b`.
2) Compute `a / b`.
3) Handle:
- divide-by-zero (`ArithmeticException`)
- invalid numeric input (Scanner mismatch or parse error)
4) Use `finally` to print `Done` (and close resources if any).

**Part 2 — Custom checked exception (marks validation)**

1) Create `InvalidMarksException extends Exception`.
2) Write method `validateMarks(int m) throws InvalidMarksException`.
3) If marks not in `0..100`, `throw new InvalidMarksException(...)`.
4) Handle in `main` with `try/catch` and print a friendly error message.

### Task B — Multithreading + synchronization (Exp-12)

Create `ThreadSyncDemo.java`:

1) Create a shared `Counter` with:
- `incUnsafe()` (no synchronization)
- `incSafe()` (use `synchronized`)

2) Create threads using:
- one `Thread` subclass **or** a `Runnable` implementation
- at least one `Runnable` implementation (as per syllabus)

3) Run two threads that increment the same counter (example: 100000 times each).
4) Use `start()` and `join()`.
5) Print final counter value for unsafe case and safe case.
6) Explain (2–4 lines): why unsafe output differs from expected.

## Deliverables

- `ExceptionHandlingDemo.java`
- `ThreadSyncDemo.java`
- Sample run/output for both programs
- Observations (5–10 lines): execution order of try/catch/finally; what a race condition is and why `synchronized` fixes it

## Optional extensions

- Add thread names and print `Thread.currentThread().getName()`.
- Demonstrate `sleep()` and explain why it should be used carefully.
