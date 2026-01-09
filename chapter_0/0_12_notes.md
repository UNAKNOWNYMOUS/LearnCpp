---
id: 0_12_notes
aliases: []
tags: []
---

# 0.12 -- Configuring your compiler: Choosing a language standard
- The conventional names for language standards (e.g. C++20) are based on the year the language standard was published (or expected to be published).
#### As an aside...
- C++11 has development name `C++0x` because it was originally expected to be published before 2010.
## Which language standard should you choose?
#### Tip
#### Author's note
#### A reminder
- When changing your language standard (or any other project setting), make the change to all build configurations.
## Setting a language standard in Visual Studio
#### Warning
#### Tip
#### Related content
## Setting a language standard in Code::Blocks
#### Warning
#### Tip
## Setting a language standard in GCC/G++/Clang
- For GCC/G++/Clang, you can use compiler options `-std=c++11`, `-std=c++14`, `-std=c++17`, `-std=c++20`, or `-std=c++23` (to enable C++11/14/17/20/23 support respectively). If you have GCC 8 or 9, you'll need to use `-std=c++2a` for C++20 support instead. You can also try the latest code name (e.g. `-std=c++2c`) for experimental support for features from the upcoming language standard.
## Setting a language standard for VS Code
## What language standard is my compiler currently using?
## Exporting your configuration
### For Visual Studio users
### For Code::Blocks users
## Where can I view the C++ standards document?
- Each C++ language standard is described by a *standards document*, which is a formal technical document that is the authoritative source for the rules and requirements of a given language standard.
## Compilers often have incomplete support for new language features
