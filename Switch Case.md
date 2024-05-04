# Switch Case Statements in Java

Switch case statements provide an efficient way to handle multiple cases of a variable. It allows the program to execute different blocks of code based on the value of a variable.

## Syntax

The syntax of the switch case statement in Java is as follows:

```java
switch (expression) {
    case value1:
        // Code block to execute if expression equals value1
        break;
    case value2:
        // Code block to execute if expression equals value2
        break;
    // Add more cases as needed
    default:
        // Code block to execute if expression does not match any case
}
- `expression` is the variable or value to be evaluated.
- `case value1`, `case value2`, etc., are the possible values of the expression.
- The `break` statement is used to exit the switch case block once a matching case is found.
- The `default` case is optional and executes if none of the other cases match the expression.

### Example
```java
import java.util.Scanner;
public class switch_case {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter Your Number 1 to 7");
        int day = sc.nextInt();

        switch (day) {
            case 1:
                System.out.println("Monday");
                break;
            case 2:
                System.out.println("Tuesday");
                break;
            case 3:
                System.out.println("Wednesday");
                break;
            case 4:
                System.out.println("Thursday");
                break;
            case 5:
                System.out.println("Friday");
                break;
            case 6:
                System.out.println( "Saturday");
                break;
            case 7:
                System.out.println("Sunday");
                break;
            default:
                System.out.println("Invalid day");
        }
        if (day <= 7){
            System.out.println("The day is: " + day);
        }else {
            System.out.println("You Enter Invalid Number");
        }

    }
}

```
