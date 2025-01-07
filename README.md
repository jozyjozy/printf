# Printf Project

The **Printf** project is part of the **École 42** curriculum. In this project, you are required to implement a simplified version of the standard `printf` function in C. The goal of this project is to understand how formatted output works in C and practice using variadic functions, as well as handling different format specifiers.

## Project Description

The goal of this project is to implement a function that mimics the behavior of the standard `printf` function. The function should be able to handle a variety of format specifiers and print them to the standard output. You will implement this function using variadic arguments, which allows the function to accept an indefinite number of arguments.

The project requires you to implement the following behavior:

1. **Basic Format Specifiers**: 
    - `%c`: Print a character.
    - `%s`: Print a string.
    - `%d`: Print an integer.
    - `%i`: Print an integer (same as `%d`).
    - `%u`: Print an unsigned integer.
    - `%x`: Print an unsigned integer in hexadecimal (lowercase).
    - `%X`: Print an unsigned integer in hexadecimal (uppercase).
    - `%p`: Print a pointer address in hexadecimal (lowercase).

2. **Edge Cases**:
    - Handle special cases like `NULL` for strings or pointers.
    - Properly handle `0` values for numeric specifiers.
    - Implement `%` as a literal character (i.e., `%%`).
