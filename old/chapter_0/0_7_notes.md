---
id: 0_7_notes
aliases: []
tags: []
---

# 0.7 -- Compiling your first program
## Projects
- A *project* is a container that holds all of your source code files, images, data files, etc... that are needed to produce an executable (or library, website, etc...) that you can run or use.
### Best practice
- Create a new project for each new program you write
## Console projects
- A *console project* means that we are going to create programs that can be run from Windows, Linux, or Mac consoles.
## Workspaces / solutions
- A workspace or solution is a container that can hold one or more related projects.
## Writing your first program
## Creating a project in Visual Studio 2019 (or newer)
### Q: What are precompiled headers and why are we turning them off?
- In larger projects (those with many code files), precompiled headers can improve compilation speed by avoiding redundant compilation that tends to occur in larger projects.
## Creating a project in Visual Studio 2017 or older
## Visual Studio Solution Explorer
### Q: I got error C1010 ("fatal error C1010: unexpected end of file while looking for precompiled header. Did you forget to add '#include "stdafx.h"' to your source?"). What now?
### Related content
## Creating a project in Code::Blocks
## Creating a project in VS Code
## If you're using g++ on the command line
## If you're using other IDEs or a web-based compiler
## If compiling fails
## If your program runs but the console window flashes and closes immediately
## What is the difference between the compile, build, rebuild, clean, and run/start options in my IDE?
- To produce an executable that can run, each code file in a program is compiled into an object file, and then the object files are linked into an executable.
- A *cache* (pronounced like "cash") is storage location where frequently accessed data is stored for fast retrieval later.
- *Build* compiles all modified code files in the project or workspace/solution, and then links the object files into an executable. If no code files have been modified since the last build, this option does nothing.
- *Clean* removes all cached objects and executables so the next time the project is built, all files will be recompiled and a new executable produced.
- *Rebuild* does a "clean", followed by a "build".
- *Compile* recompiles a single code file (regardless of whether it has been cached previously). This option does not invoke the linker or produce an executable.
- *Run/start* executes the executable from prior build. Some IDEs (e.g. Visual Studio) will invoke a "build" before doing a "run" to ensure you are running the latest version of your code. Otherwise (e.g. Code::Blocks) will just execute the prior executable.
## Conclusion
