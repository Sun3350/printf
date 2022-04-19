# 0x10. C - printf

## Description

This team project is part of the first year curriculum of ALX School.
\_printf replicates the C standard library printf() function.

What you should learn from this project:

- How to use git in a team setting
- Applying variadic functions to a big project
- The complexities of printf
- Managing a lot of files and finding a good workflow

## Prototype

`int _printf(const char *format, ...);`

## Usage

- Prints a string to the standard output, according to a given format
- All files were created and compiled on Ubuntu 14.04.4 LTS using GCC 4.8.4 with the command `gcc -Wall -Werror -Wextra -pedantic *.c`
- All files were linted for syntax and style with [Betty](https://github.com/holbertonschool/Betty)
- Returns the number of characters in the output string on success, -1 otherwise
- Call it this way: `_printf("format string", arguments...)` where `format string` can contain conversion specifiers and flags,
  along with regular characters

## Examples

- `_printf("Hello, Alx\n")` _prints "Hello, Alx", followed by a new line_
- `_printf("%s", "Hello")` _prints "Hello"_
- `_printf("This is a number: %d", 98)` _prints "This is a number: 98"_


## Author

- [Ayomide Isaac](https://github.com/Sun3350)
- [Adekey Adeniyi](https://github.com/adekeyeadeniyi) 

