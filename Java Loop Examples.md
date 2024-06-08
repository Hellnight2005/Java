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
##Java Loop Challenge: Identifying Even and Odd Numbers

## OutPut
```java
 for (int j=0; j<=100; j++){
                if(j%2 == 0){
                    System.out.println("This is even number" + j);
                }else {
                    System.out.println("This is odd number" + j);
                }
            }
```

}
```
