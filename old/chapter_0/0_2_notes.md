---
id: 0_2_notes
aliases: []
tags: []
---

# 0.2 -- Introduction to programs and programming languages
- A *computer program* is a sequence of instructions that directs a computer to perform certain actions in a specified order.
- Computer programs are typically written in a *programming language* which is a language designed to facilitate the writing of instructions for computers.
- The act (and art) of writing a program is called *programming*.
- When a computer is performing the actions described by the instructions in a computer program, we say it is *running* or *executing* the program.
- Programs are executed on the computer's *hardware*, which consists of the physical components that make up a computer.
- Notable hardware found on a typical computing device includes:
  - A CPU (Central Processing Unit, often called the "brain" of the computer), which actually executed the instructions.
  - Memory, where computer programs are loaded prior to execution.
  - Interactive devices (e.g. a monitor, touch screen, keyboard, or mouse), which allow a person to interact with a computer.
  - Storage devices (e.g. a hard drive, SSD, or flash memory), which retain information (including installed programs) even when the computer is turned off.
- In contrast, the term *software* broadly refers to the programs on a system that are designed to be executed on hardware.
- A program that can be easily transferred from one platform to another is said to be *portable*.
- The act of modifying a program so that it runs on a different platform is called *porting*.
## Machine Language
- CPUs are only capable of processing instructions written in *machine language* (or *machine code*).
- The set of all possible machine language instructions that a given CPU can understand is called an *instruction set*.
- Each instruction is composed of a sequence of 1s and 0s.
  - Each individual 0 or 1 is called a *binary digit*, or *bit* for short.
- Each family of compatible CPUs (e.g. x86, Arm64) has its own machine language, and this machine language is not compatible with the machine language of other CPU families. This means machine language programs written for one CPU family cannot be run on CPUs from a different family!
- A "CPU family" is formally called an "instruction set architecture" ("ISA" for short).
## Assembly Languages
- An *assembly language* (often called *assembly* for short) is a programming language that essentially functions as a more human-readable machine language.
- Since CPUs do not understand assembly language, assembly programs must be translated into machine language before they can be executed.
  - This translation is done by a program called an *assembler*.
## Introduction to low-level languages
- Machine languages and assembly languages are considered low-level languages.
- Low-level languages have a number of notable downsides:
  - Programs written in a low-level language are not portable.
  - Writing a program in a low-level language requires detailed knowledge or the architecture itself.
  - Low-level programs are hard to understand.
  - It is hard to write assembly programs of significant complexity because the language only provides primitive capabilities.
- The primary benefit of low-level language is that they are fast.
## Introduction to high-level Languages
- To address many of the above downsides, new "high-level" programming languages such as C, C++, Pascal (and later, languages such as Java, JavaScript, and Perl) were developed.
- Programs written in a high-level language must be translated into machine language before they can be run. There are two primary ways this is done: compiling and interpreting.
- C++ programs are usually compiled.
- A *compiler* is a program (or collection of programs) that reads the source code of one language (usually a high-level language) and translates it into another language (usually a low-level language).
  - For example, a C++ compiler translates C++ source code into machine code.
- Most C++ compilers can also be configured to generate assembly code.
- Notably, running the executable file does not require the compiler to be installed.
- Alternatively, an *interpreter* is a program that directly executes the instructions in the source code without requiring them to be compiled first.
- Another advantage of compiled programs is that distributing a compiled program does not require distributing the source code. In a non-open-source environment, this is important for intellectual property (IP) protected purposes.
## The benefits of high-level languages
- High-level languages are names as such because they provide a high level of abstraction from the underlying architecture.
- High-level languages allow programmers to write programs without knowing much about the platform it will be run on.
- This makes them:
  - Easier to write.
  - More portable.
- If we're careful, we can write a single C++ that will compile on every platform that has a C++ compiler!
- A program that is designed to run on multiple platforms is said to be *cross-platform*.
- Programs written in a high-level language are easier to read, write, and learn because their instructions more closely resemble the natural language and mathematics that we use every day.
- High-level languages typically include additional capabilities that make it easier to perform common programming tasks, such as requesting a block of memory or manipulating text.
## Rules, Best practices, and warnings
