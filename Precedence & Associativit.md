# Operator Precedence in Java

Operator precedence determines the order in which operators are evaluated in an expression. Operators with higher precedence are evaluated before operators with lower precedence. In Java, operators are categorized into different precedence levels.

## Precedence Levels

1. **Postfix Operators**:
   - `expr++`, `expr--`

2. **Unary Operators**:
   - `++expr`, `--expr`, `+expr`, `-expr`, `!expr`, `~expr`

3. **Multiplicative Operators**:
   - `*`, `/`, `%`

4. **Additive Operators**:
   - `+`, `-`

5. **Shift Operators**:
   - `<<`, `>>`, `>>>`

6. **Relational Operators**:
   - `<`, `<=`, `>`, `>=`, `instanceof`

7. **Equality Operators**:
   - `==`, `!=`

8. **Bitwise AND Operator**:
   - `&`

9. **Bitwise XOR Operator**:
   - `^`

10. **Bitwise OR Operator**:
    - `|`

11. **Logical AND Operator**:
    - `&&`

12. **Logical OR Operator**:
    - `||`

13. **Conditional Operator**:
    - `? :`

14. **Assignment Operator**:
    - `=`, `+=`, `-=` etc.


## Example

```java
int result = 10 + 5 * 2; // Evaluates as 10 + (5 * 2) = 20
```
# Operator Associativity in Java

Operator associativity determines the order in which operators of the same precedence are evaluated in an expression. In Java, operators can be left-associative, right-associative, or non-associative.

## Left-Associative Operators

Left-associative operators are evaluated from left to right. Most operators in Java are left-associative, including arithmetic operators (`+`, `-`, `*`, `/`, `%`), assignment operators (`=`, `+=`, `-=`, `*=`, `/=`), logical operators (`&&`, `||`), and bitwise operators (`&`, `|`, `^`).

## Right-Associative Operators

Right-associative operators are evaluated from right to left. The only right-associative operator in Java is the assignment operator for ternary conditional expressions (`? :`).

## Non-Associative Operators

Non-associative operators do not have an associativity defined, meaning they cannot be chained together without parentheses. The equality operators (`==`, `!=`) and the relational operators (`<`, `<=`, `>`, `>=`) are non-associative.


Understanding operator associativity is important for correctly interpreting expressions and avoiding unexpected behavior in Java programs.


![Precedence & Associativity in Java](images.png)

