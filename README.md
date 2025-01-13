# ft_printf

## Overview
The **ft_printf** project is a re-implementation of the C standard library function `printf`. The goal is to create a custom `ft_printf` function capable of formatting and printing data of various types, mimicking the behavior of the original function while learning about variadic functions and low-level output.

---

## Features
### Supported Conversion Specifiers:
| Specifier | Description                                         |
|-----------|-----------------------------------------------------|
| `%c`      | Prints a single character.                         |
| `%s`      | Prints a string of characters.                     |
| `%p`      | Prints a memory address (pointer).                 |
| `%d`/`%i` | Prints a decimal (base 10) integer.                |
| `%u`      | Prints an unsigned decimal (base 10) integer.      |
| `%x`      | Prints a lowercase hexadecimal (base 16) number.   |
| `%X`      | Prints an uppercase hexadecimal (base 16) number.  |
| `%%`      | Prints a literal `%` character.                    |

---

## Installation
1. Clone this repository:
   ```bash
   git clone clone git@github.com:d2iv3r/ft_printf.git
   cd ft_printf

## Usage

Once you've built your `libft.a` library, you can use it in your C projects by linking it during compilation. Here's how:

### 1. **Building the Library**
To build the library, run:
```bash
make
```

### To use ft_printf in your project:

Include the header file in your .c files:


```bash
#include "ft_printf.h"
```

Compile your code with the libftprintf.a library:

```bash
gcc -Wall -Wextra -Werror your_file.c -L. -lftprintf -o your_program
```

Call ft_printf in your code just like the standard printf function:

```bash
ft_printf("Hello, %s! The answer is %d.\n", "world", 1337);
```
