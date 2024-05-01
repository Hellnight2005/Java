# Calculate Percentage

This Java program calculates the percentage of total marks obtained by a student in multiple subjects.

## Code Explanation

```java
import java.util.Scanner;

public class CalculatePercentage {
    public static void main(String[] args) {
        // Create a Scanner object to read input from the console
        Scanner sc = new Scanner(System.in);
        
        // Prompt the user to enter the total marks for all subjects
        System.out.println("Total Marks of all Subject");
        int totalMarks = sc.nextInt();
        
        // Prompt the user to enter the marks for each subject
        System.out.println("Enter Your DAA Marks");
        int daaMarks = sc.nextInt();
        System.out.println("Enter Your Python Marks");
        int pythonMarks = sc.nextInt();
        System.out.println("Enter your DBMS Marks");
        int dbmsMarks  = sc.nextInt();
        System.out.println("Enter Your Calcues Marks");
        int calcuesMarks = sc.nextInt();
        System.out.println("Enter Your statices Marks");
        int statMarks = sc.nextInt();
        System.out.println("Enter Your C++ Marks");
        int cPlusPlusMarks = sc.nextInt();
        
        // Calculate the total marks obtained by summing up the marks of all subjects
        int totalObtainedMarks = daaMarks + pythonMarks + dbmsMarks + calcuesMarks + statMarks + cPlusPlusMarks;
        
        // Calculate the percentage
        double percentage = (totalObtainedMarks / (double)totalMarks) * 100;
        
        // Display the percentage
        System.out.println("The Percentage is: " + percentage + "%");
        
        // Close the scanner to release resources
        sc.close();
    }
}
