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

# File Functions

_printf.c
Own Printf Function Tha Performs Formatted Output Conversion And Print Data.

 # main.h
Header File Were All Prototypes Are Saved.

# get_print_func.c
Pointer To A Function That Selects The Correct Function To Perform The Operation.

# print_buf.c
Function That Prints The Buffer.

# handl_buf.c
Function That Concatenates The Buffer Characters.

# print_chr.c
Function That Writes The Character C To Stdout.

/* Indetifier : %c */
# print_str.c
Function That Writes The String To Stdout.

/* Indetifier : %s */
# print_int.c
Function That Prints An Integer.

/* Indetifier : %i or %d */
# print_bnr.c
Function That Prints Decimal In Binary.

/* Indetifier : %b */
# print_oct.c
Function That Prints Decimal In Octal.

/* Indetifier : %o */
# print_hex.c
Function That Prints Decimal In Hexadecimal.

/* Indetifier : %x */
# print_upx.c
Function That Prints Decimal In Uppercase Hexadecimal.

/* Indetifier : %X */
# print_usr.c
Function That Prints A String And Values Of Non-Printed Chars.

/* Indetifier : %S */
# print_unt.c
Function That Prints An Unsigned Integer.

/* Indetifier : %u */
# print_rev.c
Function That Writes The String To Stdout In Reverse.

/* Indetifier : %r */
# print_rot.c
Function That Writes The String To Stdout In Rot13.

/* Indetifier : %R */
# print_add.c
Function That Prints The Address Of An Input Variable.

/* Indetifier : %p */
# print_long_oct.c
Function That Prints Long Decimal Number In Octal.

/* Indetifier : %lo */
# print_long_hex.c
Function That Prints Long Decimal Number In Hexadecimal.

/* Indetifier : %lx */
# print_long_int.c
Function That Prints A Long Integer.

/* Indetifier : %li */
# print_long_upx.c
Function That Prints A Long Decimal In Uppercase Hexadecimal.

/* Indetifier : %lX */
# print_long_unt.c
Function That Prints A Long Unsigned Integer.

/* Indetifier : %lu */
# print_short_oct.c
Function That Prints Short Decimal Number In Octal.

/* Indetifier : %ho */
# print_short_hex.c
Function That Prints Short Decimal Number In Hexadecimal.

/* Indetifier : %hx */
# print_short_int.c
Function That Prints A Short Integer.

# print_short_upx.c
Function That Prints A Short Decimal In Uppercase Hexadecimal.

/* Indetifier : %hX */
# print_short_unt.c
Function That Prints A Short Unsigned Integer.

/* Indetifier : %hu */
# print_num_hex.c
Function That Print A Number In Hexadecimal Begining With 0 And x.

/* Indetifier : %#x */
# print_num_oct.c
Function That Prints A Number In Octal Begining With 0 And o.

/* Indetifier : %#o */
# print_num_upx.c
Function That Prints A Number In Uppercase Hexadecimal.

/* Indetifier : %#X */
# print_plus_int.c
Function That Prints An Integer With Plus Symbol.

/* Indetifier : %+i */
# print_space_int.c
Function That Prints An Integer Begining With 0 And u.

/* Indetifier : % i */
# ev_print_func.c
Function That Returns The Amount Of Indetifiers.

**Contributing**
====================
This is a project for  [ALX School](https://www.alxafrica.com/)  by ALX Students.


**Authors**
=========
- [Malachy Nwafor](https://github.com/MalachyCode)
- [Sebastian Omeje](https://github.com/Sebastianodon).
