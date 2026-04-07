# Experiment-15&16 — Lambda Expressions + GUI Programming Using Swing

This lab sheet combines **Experiment-15** and **Experiment-16** as per the lab syllabus.

## General instructions (lab manual)

- Write and execute programs independently.
- Follow standard Java coding conventions.
- Submission must include: **source code**, **output**, and brief **observations**.

## Experiment 15 (Syllabus)

**Objective:** To use lambda expressions and functional interfaces.  
**Problem Statement:** Implement lambda expressions in Java programs.  
**Expected Outcome:** Students will understand functional programming.

## Experiment 16 (Syllabus)

**Objective:** To design GUI applications using Swing.  
**Problem Statement:** Develop GUI applications using Swing components.  
**Expected Outcome:** Students will create interactive applications.

## Lab tasks (recommended scenario)

### Task A — Lambda practice (Exp-15)

Create `LambdaDemo.java`:

1) Define a custom `@FunctionalInterface` (example: `IntOp`) with method `apply(int a, int b)`.
2) Create lambdas:
- addition
- max/min
3) Create a `Runnable` using lambda and run it in a thread.
4) Sort a string array using a comparator lambda (case-insensitive).

### Task B — Swing UI with events (Exp-16)

Create `SwingDemo.java`:

1) Create a window with:
- text field for name
- button “Greet”
- label for output
- button “Reset”

2) On “Greet” click:
- increase a click counter
- update label: `Hello <name> (Clicks: X)`

3) On “Reset” click:
- counter becomes 0
- label shows reset message
- clear text field

4) Use `SwingUtilities.invokeLater(...)` (EDT best practice).

## Deliverables

- `LambdaDemo.java`
- `SwingDemo.java`
- Sample output for `LambdaDemo.java`
- Screenshot of Swing UI running (or short screen recording)
- Observations (5–10 lines): why lambdas need functional interfaces; what EDT is and why we use it

## Optional extensions

- Add a “Reverse Name” button and implement its action using a lambda listener.
- Validate empty input and show a dialog (`JOptionPane.showMessageDialog`).
