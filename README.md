# 0x11 C - printf

## Prototype
`int _printf(const char *format, ...);`

## Compilation
`$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c`

/*

File: _printf.c

Auths: ABBA SARAH

JAMES BENEDICT @ ALX-SCHOOL 
*/
DESCRIPTION The function "_printf" writes output to stdout, the standard output. The function writes under the control of a format string that specifies how subsequent arguments (accessed via the variable-length argument facilities of stdarg) are converted for output.

RETURN VALUE Upon successful return, "_printf()" returns the number of characters printed (excluding the null byte used to end output to strings).

If an output error is encountered, -1 is returned. ...
