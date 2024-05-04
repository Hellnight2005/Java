# Relational and Logical Operators in Java

In Java, relational and logical operators are used to perform comparisons and logical operations on operands. They are commonly used in conditional statements and loops to control the flow of the program.

## Relational Operators

Relational operators are used to compare two values and determine the relationship between them. Here are the relational operators in Java:

- **Equal to (`==`)**: Checks if two operands are equal.
- **Not equal to (`!=`)**: Checks if two operands are not equal.
- **Greater than (`>`)**: Checks if the left operand is greater than the right operand.
- **Less than (`<`)**: Checks if the left operand is less than the right operand.
- **Greater than or equal to (`>=`)**: Checks if the left operand is greater than or equal to the right operand.
- **Less than or equal to (`<=`)**: Checks if the left operand is less than or equal to the right operand.

## Logical Operators

Logical operators are used to perform logical operations on boolean expressions. Here are the logical operators in Java:

- **Logical AND (`&&`)**: Returns true if both operands are true.
- **Logical OR (`||`)**: Returns true if at least one of the operands is true.
- **Logical NOT (`!`)**: Returns true if the operand is false and false if the operand is true.

## Example

Consider the following example:

```java
int x = 5;
int y = 10;

// Relational operators
boolean isEqual = (x == y); // false
boolean isNotEqual = (x != y); // true
boolean isGreaterThan = (x > y); // false

// Logical operators
boolean logicalAnd = (x < 10 && y > 5); // true
boolean logicalOr = (x < 10 || y < 5); // true
boolean logicalNot = !(x == y); // true
