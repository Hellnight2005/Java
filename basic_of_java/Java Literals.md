# Java Literals

This Markdown file explains literals in Java.

## Introduction

In Java programming, a literal is a constant value that is assigned to a variable or used directly in an expression. Literals represent fixed values in code and can be of various types, including numeric literals, character literals, string literals, boolean literals, and null literals.

## Numeric Literals

Numeric literals represent numeric values and can be integers, floating-point numbers, or hexadecimal numbers.

### Integer Literals

Integer literals represent whole numbers without any fractional part.

- Decimal: These are base-10 numbers, such as `42`, `-123`.
- Octal: These are base-8 numbers, prefixed with `0`, such as `075`.
- Hexadecimal: These are base-16 numbers, prefixed with `0x` or `0X`, such as `0xFF`.

### Floating-Point Literals

Floating-point literals represent real numbers with a fractional part.

- Decimal: These are floating-point numbers with a decimal point, such as `3.14`, `-0.001`.
- Scientific Notation: These are expressed in scientific notation, such as `2.5e-3` (which equals `0.0025`).

### Examples

```java
int intValue = 42;
long longValue = 123L;
float floatValue = 3.14f;
double doubleValue = 2.5e-3;
char charValue1 = 'A';
char charValue2 = '\n'; // Newline character
char charValue3 = '\u0041'; // Unicode character for 'A'
String stringValue = "Hello, World!";
