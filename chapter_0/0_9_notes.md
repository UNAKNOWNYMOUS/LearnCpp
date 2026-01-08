---
id: 0_9_notes
aliases: []
tags: []
---

# 0.9 -- Configuring your compiler: Build configurations
- A *build configuration* (also called a *build target*) is a collection of project settings that determines how your IDE will build your project.
- A *debug configuration* is designed to help you debug your program, and is generally the one you will use when writing your programs.
- The *release configuration* is designed to be used when releasing your program to the public.
### Best practice
- Use the debug build configuration when developing your programs. When you're ready to release your executable to others, or want to test performance, use the release build configuration.
## Switching between build configurations
### For Visual Studio users
### For Code::Blocks users
### For gcc and Clang users
- Add `ggdb` to the command line for debug builds and `-O2 -DNDEBUG` for release builds.
- `-O0` `-O2` `-O3` are used to optimization.
### For VS Code users
## Modifying build configurations
### Tip
- Whenever you update your project settings, make the change for all build configurations (unless it's not appropriate for some reason).
