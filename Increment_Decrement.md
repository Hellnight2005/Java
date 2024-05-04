# Increment/Decrement Operators in Java

This Markdown file explains the usage of increment and decrement operators in Java.

## Increment Operator (++)

The increment operator (`++`) is a unary operator used to increase the value of a variable by 1. It can be used in two forms: prefix and postfix.

### Prefix Increment

Prefix increment (`++variable`) first increments the value of the variable and then returns the updated value.

```java
int x = 5;
int result = ++x; // Increment x first, then assign to result
// Now, x = 6 and result = 6

# Increment/Decrement Operators in Java

This Markdown file explains the usage of increment and decrement operators in Java.

## Explanation

Increment (`++`) and decrement (`--`) operators are unary operators used to increase or decrease the value of a variable by 1, respectively. They can be used in prefix or postfix form.

- **Prefix Increment/Decrement**: First increments or decrements the value of the variable and then returns the updated value.
- **Postfix Increment/Decrement**: First returns the current value of the variable and then increments or decrements it.

## Java Program

```java
public class IncrementDecrementExample {
    public static void main(String[] args) {
        int x = 5;

        // Prefix Increment
        int prefixIncrementResult = ++x;
        System.out.println("Prefix Increment: " + prefixIncrementResult); // Output: 6

        // Reset x
        x = 5;

        // Postfix Increment
        int postfixIncrementResult = x++;
        System.out.println("Postfix Increment: " + postfixIncrementResult); // Output: 5 (x is incremented after assigning to postfixIncrementResult)

        // Reset x
        x = 5;

        // Prefix Decrement
        int prefixDecrementResult = --x;
        System.out.println("Prefix Decrement: " + prefixDecrementResult); // Output: 4

        // Reset x
        x = 5;

        // Postfix Decrement
        int postfixDecrementResult = x--;
        System.out.println("Postfix Decrement: " + postfixDecrementResult); // Output: 5 (x is decremented after assigning to postfixDecrementResult)
    }
}
