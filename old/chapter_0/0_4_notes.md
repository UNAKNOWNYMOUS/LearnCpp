---
id: 0_4_notes
aliases: []
tags: []
---

# 0.4 -- Introduction to C++ development
## Step 1: Define the problem that you would like to solve
- This is the "what" step, where you figure out what problem you are intending to solve.
## Step 2: Determine how you are doing to solve the problem
- This is the "how" step, where you determine how you are going to solve the problem you came up with in step 1.
  - It is also the step that is most neglected in software development.
- Typically, good solutions have the following characteristics:
  - They are straightforward (no overly complicated or confusing).
  - They are well documented (especially around any assumptions being made or limitations).
  - They are built modularly, so parts can be reused or changed later without impacting other parts of the program.
  - They can recover gracefully or give useful error messages when something unexpected happens.
- A *bug* is any kind of programming error that prevents the program from operating correctly.
- Various studies have shown that on complex software systems, only 10-30% of a programmer's time is actually spent writing the initial program.
- The other 60-90% is spend on maintenance, which consist of *debugging* (removing bugs), updates to cope with changes in the environment (e.g. to run on a new OS version), enhancements (minor changes to improve usability or capability), or internal improvements (to increase reliability or maintainability).
## Step 3: Write the program
- The set of C++ instructions that we input into the text editor is called the program's *source code* (often shortened to just *code*).
- Many simple C++ programs only have one source code file, but complex C++ programs can have hundreds or even thousands of source code files.
- C++ does not have any requirement for naming files.
  - However, the de-facto standard is to name the first/primary source file created for a program `main.cpp`.
- You may occasionally see the first/primary source code file named after the name of the program instead (e.g. `calculator.cpp`, `poker.cpp`). You may also occasionally see other extensions user (e.g. `.cc` or `.cxx`).
### Best practice
- Name the first/primary source code file in each program `main.cpp`. This makes it easy to determine which source code file is the primary one.
