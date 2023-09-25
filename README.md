# Custom printf function

This project is a part of the ALX Software Engineering program, aimed at creating a custom version of the standard C library function "printf". The goal of this project is to implement a subset of the functionality provided by the original "printf" function, including formatting strings, integers, and floating-point numbers.

## Usage

To use the custom "printf" function, simply include the "holberton.h" header file in your C program and call the "printf" function with the desired formatting options. For example:

```c
#include "spoutnikrs.h"

int main(void)
{
    int num = 123;
    char *str = "Hello, world!";
    
    _printf("String: %s, integer: %d\n", str, num);
    
    return (0);
}
```

This would output:

```
String: Hello, world!, integer: 123
```

## Supported format specifiers

The following format specifiers are supported by the custom "printf" function:

- `%c`: prints a single character
- `%s`: prints a string of characters
- `%d`: prints a signed decimal integer
- `%i`: prints a signed decimal integer
- `%b`: prints an unsigned binary number
- `%u`: prints an unsigned decimal integer

## Project requirements

To complete this project, the custom "printf" function must meet the following requirements:

- It must handle the format specifiers listed above
- It must be able to handle variable argument lists
- It must be able to handle optional flags and modifiers, such as the width and precision specifiers
- It must be able to handle multiple format specifiers in a single call to "printf"
