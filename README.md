# printf
This repository contains code for a printf function I and my colleague, Sebastian Omeje, created.

- This repository includes our version of the printf function, the basic and main functions. Here we will apply the knowledge that we have acquired during the learning of the programming language C.
- This project is requested by ALX School.
---------------
**Description**
================
The printf function prints a format control string of different data types on the standard output, its roots are in the C programming language, it is a functional way to produce a precise output format for printing numerical values or ASCII characters from format specifiers that have been passed on in the argument.

**Prototype**
=================
This printf function produces output according to a format:

    int _printf(const char *format, ...);

**Formats**
=================
|flag|function|
|--|--|
|%c|print a single character|
|%s|print a string|
|%%|print a percentage
|%d|print a integer as a signed decimal (base 10) number|
|%i|print same as "d", integer in base 10|

**Compilation**
====================
To compile a file with the function is necessary to add all the .c files involved in the program (functions, main files, etc). Your code will be compiled this way:

    gcc -Wall -Werror -Wextra -pedantic *.c -o name_of_executable

To execute: `./name_of_executable`

# Examples

Character: printf("%c", A); Output:: A

String: printf("%s", This is a string.); Output: This is a string.

Integer: printf("%i", 5); Output: 5

**Contributing**
====================
This is a project for  [ALX School](https://www.alxafrica.com/)  by ALX Students.


**Authors**
=========
- [Malachy Nwafor](https://github.com/MalachyCode)
- [Sebastian Omeje](https://github.com/Sebastianodon).
