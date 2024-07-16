## Makefile Overview

The `Makefile` provided in this repository demonstrates basic concepts:

### C++ Project (`/CPP/Makefile`)

- **Compiling C++ Source Files**:
  - C++ source files (`*.cpp`) are compiled into object files (`*.o`) using the `g++` compiler.
  - Target: Default target `all` compiles all source files into object files and links them into an executable named `myprogram`.

- **Cleaning Up**:
  - The `clean` target removes all generated object files (`*.o`) and the executable (`myprogram`).