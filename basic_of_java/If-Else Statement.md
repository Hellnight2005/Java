## If-Else Statement in Java

The if-else statement is a fundamental control flow statement in Java used to execute code based on a condition. It allows your program to make decisions based on the evaluation of a boolean expression.
### Syntax
The syntax of the if-else statement in Java is as follows:
```java
if (condition) {
    // Code block to execute if the condition is true
} else {
    // Code block to execute if the condition is false
}
```

### Example
Consider the following example:

  ```java

    int number = 10;

  if (number > 0) {
      System.out.println("Number is positive");
  } else {
      System.out.println("Number is non-positive");
  }
```
## Nested If-Else Statements Syntax

You can nest if-else statements within each other to create more complex decision-making structures.

### Syntax

The syntax for nested if-else statements in Java is as follows:

```java
if (condition1) {
    // Code block to execute if condition1 is true
    if (condition2) {
        // Code block to execute if both condition1 and condition2 are true
    } else {
        // Code block to execute if condition1 is true but condition2 is false
    }
} else {
    // Code block to execute if condition1 is false
}
```


### Example

```java
int number = 10;

if (number > 0) {
    if (number % 2 == 0) {
        System.out.println("Number is positive and even");
    } else {
        System.out.println("Number is positive and odd");
    }
} else if (number == 0) {
    System.out.println("Number is zero");
} else {
    System.out.println("Number is negative");
}
