---
id: 0_10_notes
aliases: []
tags: []
---

# 0.10 -- Configuring your compiler: Compiler extensions
- The C++ standard defines rules about how your program should behave in specific circumstances.
  - And in most cases, compilers will follow these rules.
- However, many compilers implement their own changes to the language, often to enhance compatibility with other versions of the language (e.g. C99), or for historical reasons.
  - These compiler-specific behaviors are called *compiler extensions*.
### Best practice
- Disable compiler extensions to ensure your programs (and coding practices) remain compliant with C++ standards and will work on any system.
## Disabling compiler extensions
### For Visual Studio users
### For Code::Blocks users
### For gcc and Clang users
- You can disable compiler extensions by adding the `-pedantic-errors` flag to the compile command line.
### For VS Code users
#### Related content
#### A reminder
- These settings are applied on a per-project basis. You need to set them every time you create a new project, or create a template project with those settings once and use that to create new projects.
