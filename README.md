A simple printf function built by Ademileke Abudu and Beryl Wawuda for Alx Software Engineering School.

#Welcome

Rebuild of the standard printf function in C. Our project required a function capable of printing with the %d, %c, %s, and %% specifier to standard output. printf returns the number of characters printed (excluding the null byte at the end of strings). We were not asked to handle flag characters, field width, precision, or length.

#Format Specifiers

Our team chose to add %x ,%X, %b, %o, %u, %r, %R, and %p formatting. We relied on the library we have been building at Alx as well as new concepts gathered during this project.

#Supported Format Types

TYPE - OUTPUT

c - Single character

s - String

r - String in reverse

R - String in rot13

d - Integer in decimal

i - integer

% - Percent sign

Xl - Lowercase hex

X - Uppercase hex

b - binary

o - octal

u - unsigned

p - pointer

F - expletive

#Examples

Character: printf("%c", A); Output:: A

String: printf("%s", This is a string.); Output: This is a string.

Integer: printf("%i", 5); Output: 5


The prototypes of all your functions should be included in your header file called main.h Don’t forget to push your header file All your header files should be include guarded Note that we will not provide the _putchar function for this project GitHub There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.

#Authorized functions and macros

write (man 2 write) malloc (man 3 malloc) free (man 3 free) va_start (man 3 va_start) va_end (man 3 va_end) va_copy (man 3 va_copy) va_arg (man 3 va_arg)

#Authors

Ademileke abudu

Beryl Wawuda
