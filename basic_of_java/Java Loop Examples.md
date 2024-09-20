# Java Loop Examples

This repository contains examples of various loops in Java: while loop, do-while loop, and for loop.

## Code

```java
public class Loops {
    public static void main(String[] args) {
        // Syntax of while loop
        int a = 0;
        System.out.println("While loop from 0 to 300:");
        while (a <= 300) {
            System.out.println(a);
            a++;
        }
        System.out.println(); // Adding a blank line for better readability

        // Syntax of do-while loop
        int b = 0;
        System.out.println("Do-While loop from 0 to 4:");
        do {
            System.out.println(b);
            b++;
        } while (b < 5);
        System.out.println(); // Adding a blank line for better readability

        // Syntax of for loop
        System.out.println("For loop from 1 to 10:");
        for (int i = 1; i <= 10; i++) {
            System.out.println(i);
        }
        System.out.println("\nThank you");
    }
```
## Java Loop Challenge: Identifying Even and Odd Numbers

## OutPut
```java
 for (int j=0; j<=100; j++){
                if(j%2 == 0){
                    System.out.println("This is even number" + j);
                }else {
                    System.out.println("This is odd number" + j);
                }
            }
}
```
# Break and Continue in Java
## Break Statement
The break statement is used to exit a loop immediately, regardless of the iteration number. When a break statement is encountered inside a loop, the loop terminates and control resumes at the next statement following the loop.
```java
public class BreakExample {
    public static void main(String[] args) {
        for (int i = 0; i <= 10; i++) {
            if (i == 5) {
                break; // Exit the loop when i is 5
            }
            System.out.println("Number: " + i);
        }
        System.out.println("Loop terminated.");
    }
}
```
# output 
```java 
Number: 0
Number: 1
Number: 2
Number: 3
Number: 4
Loop terminated.
```
## Continue Statement
The continue statement is used to skip the current iteration of the loop and proceed to the next iteration. When a continue statement is encountered inside a loop, the remaining code inside the loop is skipped for the current iteration.
```java
public class ContinueExample {
    public static void main(String[] args) {
        for (int i = 0; i <= 10; i++) {
            if (i == 5) {
                continue; // Skip the rest of the loop body when i is 5
            }
            System.out.println("Number: " + i);
        }
        System.out.println("Loop completed.");
    }
}

```
# output 
```java 
Number: 0
Number: 1
Number: 2
Number: 3
Number: 4
Number: 6
Number: 7
Number: 8
Number: 9
Number: 10
Loop completed.
```
