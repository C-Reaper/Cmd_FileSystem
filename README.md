# Project README

## Overview
The project is a simple file system manager implemented in C. It provides basic operations such as creating and deleting files within a simulated directory structure.

## Features
- Creating files within a directory.
- Deleting files within a directory.
- Printing the current state of the directory structure.

## Project Structure
### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools

## Build & Run
To build the project:
1. Navigate to the project directory.
2. Use `make -f Makefile.(os) all` where `(os)` is either `linux`, `windows`, `wine`, or `web`.

For example, on a Linux system:
```sh
cd <Project>
make -f Makefile.linux all
```

To run the project:
1. Navigate to the project directory.
2. Use `make -f Makefile.(os) exe` where `(os)` is either `linux`, `windows`, `wine`, or `web`.

For example, on a Linux system:
```sh
cd <Project>
make -f Makefile.linux exe
```

This will compile the source code and execute the resulting binary.