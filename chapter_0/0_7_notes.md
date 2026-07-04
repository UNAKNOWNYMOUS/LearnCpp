---
id: 0_7_notes
aliases: []
tags: []
---

# 0.7 -- Compiling your first program
## Projects
- A project is a container that holds all of your source code files, images, data files, etc... that are needed to produce an executable (or library, website, etc...) that you can run or use.
- Best practice: Create a new project for each new program you write.
## Console projects
- A console project means that we are going to create programs that can be run from the Windows, Linux, or Mac console.
## Workspaces / solutions
## Writing your first program
## Creating a project in Visual Studio 2019 (or newer)
- Q: What are precompiled headers and why are we turning them off?
## Creating a project in Visual Studio 2017 or older
## Visual Studio Solution Explorer
- Q: I got error C1010 ("fatal error C1010: unexpected end of file while looking for precompiled header. Did you forget to add '\#include "stdafx.h"' to your source?"). What now?
- Related content
## Creating a project in Code::Blocks
- For Linux users:
## Creating a project in VS Code
## If you're using g++ on the command line
## If you're using other IDEs or a web-based compiler
## If compiling fails
## If your program runs but the console window flashes and closes immediately
- Tip
## What is the difference between the compile, build, rebuild, clean, and run/start options in my IDE?
- To produce an executable that can be run, each code file in a program is compiled into an object file, and then the object files are linked into an executable.
- When a code file is compiled, your IDE may cache (save) the resulting object file on disk.
- A cache is storage location where frequently accessed data is stored for fast retrieval later.
  - That way, if the program is compiled again in the future, any code file that hasn't been modified doesn't need to be recompiled -- the cached object file from last time can be reused (rather than having to be regenerated). This can speed up compilation times significantly (at the cost of a little bit of disk space).
- Build - compiles all modified code files in the project workspace/solution, and then links the object files into an executable. If not code files have been modified since the last build, this option does nothing.
- Clean removes all cached objects and executables so the next time the project is built, all files will be recompiled and a new executable produced.
- Rebuild - does a "clean", followed by a "build".
- Compile - recompiles a single code file (regardless of whether it has been cached previously). This option does not invoke the linker or produce an executable.
- Run/start executes the executable from a prior build. Some IDEs (e.g. Visual Studio) will invoke a "build" before doing a "run" to ensure you are running he latest version of your code. Otherwise (e.g. Code::Blocks) will just execute the prior executable.
## Conclusion
