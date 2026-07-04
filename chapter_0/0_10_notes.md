---
id: 0_10_notes
aliases: []
tags: []
---

# 0.10 -- Configuring your compiler: Compiler extensions
- The C++ standard defines rules about how program should behave in specific circumstances. And in most cases, compilers will follow these rules. However, many compilers implement their own changes to the language, often to enhance compatibility with other versions of the language (e.g. C99), or for historical reasons. These compiler-specific behaviors are called compiler extensions.
- Writing a program that makes use of a compiler extension allows you to write programs that are incompatible with the C++ standard.
  - Programs using non-standard extensions generally will not compile on other compilers (that don't support those same extensions), or if they do, they may not run correctly.
- Best practice: Disable compiler extensions to ensure your programs (and coding practices) remain compliant with C++ standards and will work on any system.
## Disabling compiler extensions
- For Visual Studio users:
- For Code::Blocks users:
- For gcc and Clang users: Add the option `-pedantic-errors`.
- For VS Code users:
- Related content:
- A reminder:
