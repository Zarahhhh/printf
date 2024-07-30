# Custom printf Project

## Overview

This project involves creating a custom implementation of the C library function `printf`. The function will produce output according to a format, supporting specific conversion specifiers. This is part of a project for learning and applying fundamental concepts in C programming, including variadic functions, string handling, and formatted output.

## Features

- Supported Conversion Specifiers:
  - `%c`: Character
  - `%s`: String
  - `%d`, `%i`: Integer
  - `%%`: Literal `%` character

## Requirements

- Editors: vi, vim, emacs
- Compilation: The project will be compiled on Ubuntu 20.04 LTS using `gcc` with the following options: `-Wall -Werror -Wextra -pedantic -std=gnu89`.
- Style: The code will follow the Betty style guide.
- Restrictions: No global variables and no more than 5 functions per file.
- Header File: All function prototypes will be declared in a header file named `main.h`.

## Compilation

To compile the code, use the following command:
```sh
gcc -Wall -Wextra -Werror -pedantic -std=gnu89 *.c -o printf
