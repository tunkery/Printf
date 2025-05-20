# FT_PRINTF

This project is about recreating the `printf` function according to the coding standards of 42 School.

## Why `printf`?

The purpose of this project is to teach us how to work with **variadic functions**, and `printf` is a great candidate due to its complexity and flexibility.

## Project Requirements

You must re-implement the behavior of the standard `printf` function, supporting the following format specifiers:

- `%c` : Prints a single character.
- `%s` : Prints a string.
- `%p` : Prints a pointer address in hexadecimal format.
- `%d` : Prints a signed decimal (base 10) integer.
- `%i` : Same as `%d`, prints a signed integer.
- `%u` : Prints an unsigned decimal (base 10) integer.
- `%x` : Prints a number in lowercase hexadecimal (base 16).
- `%X` : Prints a number in uppercase hexadecimal (base 16).
- `%%` : Prints a literal percent sign.

 
## Learning Outcomes

- Mastering variadic functions (`va_start`, `va_arg`, `va_end`)
- Practicing buffer management and low-level output with `write`
- Gaining deeper knowledge of formatting rules and edge cases

## Note

This implementation is built from scratch without using the standard `printf` from the C library, as per the project’s requirements.
