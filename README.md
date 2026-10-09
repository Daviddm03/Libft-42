# Libft

My implementation of Libft, the first project of the 42 curriculum.

The goal is to build a personal C library by recreating common functions from the standard C library and implementing additional utilities that can be reused in future projects.

## About

Libft covers several areas of C programming:

- Character validation and conversion
- String manipulation
- Memory operations
- String and number conversion
- File descriptor output
- Dynamic memory allocation
- Linked lists

The bonus part adds utilities for creating, traversing, modifying, and deleting linked lists.

## Getting Started

### Requirements

- GCC or Clang
- Make
- A Unix-like environment

Clone the repository:

```bash
git clone git@github.com:Daviddm03/Libft-42.git
cd Libft-42
```

Compile the mandatory library:

```bash
make
```

This creates:

```text
libft.a
```

To include the bonus linked-list functions:

```bash
make bonus
```

Other available commands:

```bash
make clean
make fclean
make re
```

## Using the Library

Include the header in your C program:

```c
#include "libft.h"
```

Then compile your program with the library:

```bash
cc main.c libft.a -o program
./program
```

## What I Learned

Libft was my first larger C project after the Piscine.

It made me more comfortable with pointers, memory allocation, string manipulation, linked lists, header files, Makefiles, and organizing reusable code across multiple source files.

## Tech

C · Makefile · Static Libraries · UNIX
