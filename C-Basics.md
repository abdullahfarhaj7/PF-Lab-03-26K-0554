# C Programming Basics – Lab 03

## 1. Data Types

| Data Type | Description                                      | Size (bytes)     |
|-----------|--------------------------------------------------|------------------|
| int       | Whole numbers (positive, negative, zero)         | at least 2, usually 4 |
| float     | Real numbers with 6 digits precision             | 4                |
| double    | Real numbers with 14 digits precision            | 8                |
| char      | Single character                                 | 1                |
| bool      | true (1) or false (0)                            | 1                |
| void      | No value / empty                                 | –                |

## 2. Format Specifiers

| Specifier | Meaning                          |
|-----------|----------------------------------|
| %d / %i   | Signed integer                   |
| %u        | Unsigned integer                 |
| %o        | Octal                            |
| %x        | Hexadecimal (lowercase)          |
| %X        | Hexadecimal (uppercase)          |
| %f        | Floating-point                   |
| %e / %E   | Scientific notation              |
| %g        | Compact floating-point           |
| %c        | Character                        |
| %s        | String                           |
| %ld       | Long integer                     |

## 3. Important Input/Output Functions

- `printf()` → Displays output
- `scanf()` → Takes input from user
- `getchar()` → Reads a single character
- `putchar()` → Displays a single character
- `fgets()` → Safer way to read strings
- `puts()` → Displays a string + newline

## 4. Escape Sequences (at least 5)

- `\n` → New line
- `\t` → Horizontal tab
- `\\` → Backslash
- `\"` → Double quote
- `\'` → Single quote

## 5. Precision

We control the number of digits after the decimal point like this:

```c
printf("%.2f", num);   // 2 digits after decimal
printf("%.4f", num);   // 4 digits after decimal
printf("%.6f", num);   // 6 digits after decimal
