# C Hello World Example

This repository contains a minimal cross-platform "Hello, World!" implementation in C, designed to work consistently across Windows, macOS, Linux, Solaris, FreeBSD, OpenBSD, and other POSIX-compliant systems.

## Purpose

The primary goals of this repository are:

1. Demonstrate the minimal code required to write and run a C program
2. Serve as a basic test for C development environments
3. Provide a starting point for learning and experimentation

## Building and Running

### Linux
```bash
# Using GCC
gcc main.c -o hello
./hello

# Using Clang
clang main.c -o hello
./hello
```

### macOS
```bash
# Using Clang (default)
clang main.c -o hello
./hello

# Using GCC if installed
gcc main.c -o hello
./hello
```

### BSD (FreeBSD, OpenBSD)
```bash
# Using Clang (default on FreeBSD)
clang main.c -o hello
./hello

# Using GCC if installed
gcc main.c -o hello
./hello
```

### Solaris
```bash
# Using GCC
gcc main.c -o hello
./hello

# Using Sun C compiler
cc main.c -o hello
./hello
```

### Windows
```cmd
# Using Microsoft Visual C++
cl main.c
hello.exe

# Using MinGW GCC
gcc main.c -o hello.exe
hello.exe
```

## Contributing

While this repository aims to maintain minimalism, bug fixes and improvements to documentation are welcome. Please ensure any changes maintain the simplicity and cross-platform compatibility of the example.
