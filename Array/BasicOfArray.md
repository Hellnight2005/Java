# BasicOfArray Java Program

## Description
This Java program demonstrates the initialization and usage of integer and string arrays. It includes:
- Initializing an integer array with a fixed size and assigning values to specific indices.
- Initializing an integer array with predefined values.
- Initializing a string array with predefined values.
- Printing the values of the arrays.

## Code
```java
package array;
import java.util.*;

public class BasicOfArray {
    public static void main(String[] args) {
        // Initializing an integer array with a fixed size of 6
        int ageArr[] = new int[6];

        ageArr[0] = 7;
        ageArr[1] = 78;
        ageArr[2] = 0; // Initialize missing index 2
        ageArr[3] = 75;
        ageArr[4] = 75;
        ageArr[5] = 0; // Initialize missing index 5

        System.out.println(ageArr[0]);
        System.out.println(ageArr[1]);
        System.out.println(ageArr[2]);
        System.out.println(ageArr[3]);
        System.out.println(ageArr[4]);
        System.out.println(ageArr[5]);
        System.out.println(ageArr.length);

        // Initializing an integer array with given values
        int mark[] = {99, 98, 75, 26, 35, 15};

        for (int i = 0; i < mark.length; i++) {
            System.out.println("Mark At Index [" + i + "] = " + mark[i]);
        }

        // Initializing a string array with given values
        String names[] = {"abhi", "dastu", "prajyot", "sarthak", "deepak"};
        for (String name:names){
            System.out.println( "Name ["+name+"] ");
        }
    }
}
```
