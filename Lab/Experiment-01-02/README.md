# Experiment-01&02 — Java Programming Environment + Input Handling & Command Line Args

This lab sheet combines **Experiment-01** and **Experiment-02** as per the lab syllabus.

## General instructions (lab manual)

- Write and execute programs independently.
- Follow standard Java coding conventions.
- Submission must include: **source code**, **output**, and brief **observations**.

## Experiment 01 (Syllabus)

**Objective:** Understand Java programming environment, program structure, compilation, and execution process.  
**Problem Statement:** Design and implement a basic Java program demonstrating class declaration, `main()` method, and standard output statements.  
**Tasks to be performed (as per manual):**
- Install and configure JDK
- Write a basic Java program
- Compile and execute the program
- Observe compilation and runtime behavior
**Constraints/Guidelines (as per manual):**
- Follow Java syntax and standards
- Use meaningful identifiers
**Expected Outcome:** Ability to write, compile, and execute a basic Java program.

## Experiment 02 (Syllabus)

**Objective:** Understand different methods of input handling in Java.  
**Problem Statement:** Develop a Java program that accepts input using standard input methods and command line arguments.  
**Tasks to be performed (as per manual):**
- Use `Scanner` or `BufferedReader`
- Process command line arguments
- Display formatted output
**Expected Outcome:** Ability to handle input from multiple sources.

## Lab tasks (recommended scenario)

### Task A — Environment setup + first program (Exp-01)

1) Verify installation:
- `java -version`
- `javac -version`

2) Create and run `HelloUPES.java` that prints:
- a welcome message
- Java version (`System.getProperty("java.version")`)
- number of command line arguments

3) Run:
- without arguments
- with 2 arguments

### Task B — Input handling + command line args (Exp-02)

Create `InputArgsDemo.java` that:

1) Reads from command line:
- `bonusPercent` (example: `10`)

2) Reads from keyboard:
- `name` (string)
- `baseSalary` (double)

3) Computes and prints:
- `finalSalary = baseSalary + baseSalary * bonusPercent / 100`

4) Validations:
- check `args.length` before accessing `args[0]`
- handle invalid bonus argument (`NumberFormatException`)
- handle invalid salary input (`InputMismatchException`)

## Deliverables

- `HelloUPES.java`
- `InputArgsDemo.java`
- Output screenshots or copied output for both tasks
- Observations (5–10 lines): what happens at compile time vs runtime; what happens for invalid input

## Optional extensions

- Add `age` input and print eligibility to vote (>= 18).
- Validate: `bonusPercent` must be between 0 and 100.
