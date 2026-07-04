---
id: 0_2_notes
aliases: []
tags: []
---

# 0.2 -- Introduction to programs and programming languages
- A computer program is a sequence of instructions that directs a computer to perform certain actions in a specified order.
- Computer programs are typically written in a programming language, which is a language designed to facilitate the writing of instructions for computers.
- Programs are executed on the computer's hardware, which consists of the physical components that make up a computer.
- Notable hardware found on a typical computing device includes:
  - A CPU (central processing unit, often called the "brain" of the computer), which actually executes the instructions.
  - Memory, where computer programs are loaded prior to execution.
  - Interactive devices (e.g. a monitor, touch screen, keyboard, or mouse), which allow a person to interact with a computer.
  - Storage devices (e.g. a hard drive, SSD, or flash memory), which retain information (including installed programs) even when the computer is turned off.
- In contrast, the term software broadly refers to the programs on a system that are designed to be executed on hardware.
- If a program uses capabilities or services provided by the platform, it becomes dependent on that platform, and cannot be run on other platforms without modification.
- A program that can be easily transferred from one platform to another is said to be portable.
- The act of modifying a program so that it runs on a different platform is called porting.
## Machine Language
- CPUs are only capable of processing instructions written in machine language (or machine code).
- The set of all possible machine language instructions that a given CPU can understand is called an instruction set.
- Each instruction is composed of a sequence of 1's and 0's.
  - Each individual 0 or 1 is called a binary digit, or bit for short.
- Each family of compatible CPUs (e.g. x86, Arm64) has its own machine language, and this machine language is not compatible with the machine language of other CPU families. This means machine language programs written for one CPU family cannot be run on CPUs from a different family!
- Related content: A "CPU family" is formally called an "instruction set architecture".
## Assembly Languages
- An assembly language (often called assembly for short) is a programming language that essentially functions as a more human-readable machine language.
- Optional reading: None
- Since CPUs do not understand assembly language, assembly programs must be translated into machine language before they can be executed.
  - This translation is done by a program called an assembler.
  - Because each assembly language instruction is typically designed to mirror an equivalent machine language instruction, the translation process is typically straightforward.
- Just like each CPU family has its own machine language, each CPU family also has its own assembly language (which is designed to be assembled into machine langugage for that same CPU family).
  - This means there are many different languages. Although conceptually similar, different assembly languages support different instructions, use different naming conventions, etc...
## Introduction to low-level languages
## Introduction to high-level languages
- A compiler is a program (or collection of programs) that reads the source code of one language (usually a high-level language) and translates it into another language (usually a low-level language). For example, a C++ compiler translates C++ source code into machine code.
- "Optional reading": Most C++ compilers can also be configured to generate  assembly code. This is useful when a programmer wants to see what specific instructions the compiler is generating for a section of the program.
- An interpreter is a program that directly executes the instructions in the source code without requiring them to be compiled first. Interpreters tend to be more flexible than compilers, but are less efficient when running programs because the interpreting process needs to be done every time the program is run. This also means the interpreter must be installed on every machine where an interpreted program will be run.
- Optional reading: Another advantage of compiled programs is that distributing a compiled program does not require distributing the source code. In a non-open-source environment, this is important for intellectual property (IP) protection purposes.
## The benefits of high-level languages
- High-level languages are named as such because they provide a high level abstraction from the underlying architecture.
- High-level languages allow programmers to write programs without knowing much about the platform it will be run on. This not only makes programs easier to write, it also makes them significantly more portable. If we're careful, we can write a single C++ that will compile on every platform that has a C++ compiler! A program that is designed to run on multiple platforms is said to be cross-platform.
- For advanced readers: None
- Nomenclature: None
- Author's note: None
## Rules, Best practices, and warnings
- As we proceed through these tutorials, we'll highlight many important points under the following three categories: "Rules", "Best practice", and "Warning".
