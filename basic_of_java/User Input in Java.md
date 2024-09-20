
# User Input in Java

This Markdown file explains how to take user input in Java using a `Scanner` class.

## Introduction

User input is essential for interactive Java programs. The `Scanner` class in Java provides methods for reading user input from the console.

## Code Explanation

```java
import java.util.Scanner;

public class UserInput {
    public static void main(String[] args) {
        // Create a Scanner object to read input from the console
        Scanner scanner = new Scanner(System.in);
        
        // Prompt the user for input
        System.out.print("Enter your name: ");
        
        // Read the user's input as a string
        String name = scanner.nextLine();
        
        // Display a greeting message with the user's input
        System.out.println("Hello, " + name + "!");
        
        // Prompt for an integer input
        System.out.print("Enter your age: ");
        
        // Read the user's input as an integer
        int age = scanner.nextInt();
        
        // Display the user's age
        System.out.println("Your age is: " + age);
        
        // Prompt for a floating-point input
        System.out.print("Enter your height (in meters): ");
        
        // Read the user's input as a float
        float height = scanner.nextFloat();
        
        // Display the user's height
        System.out.println("Your height is: " + height + " meters");
                
        // Read the next token as a string
        System.out.print("Enter a word: ");
        String word = scanner.next();
        System.out.println("You entered: " + word);
        
        // Close the scanner to release resources
        scanner.close();
    }
}
