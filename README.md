# Null Pointer Dereference Bug in C++

This repository demonstrates a common C++ bug: dereferencing a null pointer.  The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides a corrected version.  Null pointer dereferences are a frequent cause of crashes and undefined behavior in C++ programs.  It's crucial to always check for null pointers before dereferencing them.

## How to Reproduce

1. Compile `bug.cpp` using a C++ compiler (e.g., g++).
2. Run the compiled executable.  You should observe a segmentation fault or similar error.

## Solution

The `bugSolution.cpp` file shows how to avoid this error by checking for a null pointer before accessing its value. This simple check can prevent major runtime issues.