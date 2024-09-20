# String Methods in Java

Java provides a variety of methods for manipulating strings. Here are some commonly used ones:

1. **charAt(int index)**: Returns the character at the specified index within the string.
   - Parameters:
     - `index`: The index of the character to retrieve.
   - Example:
     ```java
     String str = "Hello";
     char ch = str.charAt(0); // Returns 'H'
     ```

2. **length()**: Returns the length of the string.
   - Example:
     ```java
     String str = "Hello";
     int length = str.length(); // Returns 5
     ```

3. **substring(int beginIndex)**: Returns a substring starting from the specified index.
   - Parameters:
     - `beginIndex`: The starting index of the substring.
   - Example:
     ```java
     String str = "Hello";
     String substr = str.substring(2); // Returns "llo"
     ```

4. **substring(int beginIndex, int endIndex)**: Returns a substring starting from the specified `beginIndex` and ending at the specified `endIndex` (exclusive).
   - Parameters:
     - `beginIndex`: The starting index of the substring.
     - `endIndex`: The ending index of the substring (exclusive).
   - Example:
     ```java
     String str = "Hello";
     String substr = str.substring(1, 4); // Returns "ell"
     ```

5. **indexOf(String str)**: Returns the index within the string of the first occurrence of the specified substring.
   - Parameters:
     - `str`: The substring to search for.
   - Example:
     ```java
     String str = "Hello";
     int index = str.indexOf("l"); // Returns 2
     ```

6. **lastIndexOf(String str)**: Returns the index within the string of the last occurrence of the specified substring.
   - Parameters:
     - `str`: The substring to search for.
   - Example:
     ```java
     String str = "Hello";
     int index = str.lastIndexOf("l"); // Returns 3
     ```

7. **toLowerCase()**: Converts all characters in the string to lowercase.
   - Example:
     ```java
     String str = "Hello";
     String lowerCaseStr = str.toLowerCase(); // Returns "hello"
     ```

8. **toUpperCase()**: Converts all characters in the string to uppercase.
   - Example:
     ```java
     String str = "Hello";
     String upperCaseStr = str.toUpperCase(); // Returns "HELLO"
     ```

9. **trim()**: Removes leading and trailing whitespace from the string.
   - Example:
     ```java
     String str = "  Hello  ";
     String trimmedStr = str.trim(); // Returns "Hello"
     ```

10. **replace(char oldChar, char newChar)**: Replaces all occurrences of a specified character with another character.
    - Parameters:
      - `oldChar`: The character to be replaced.
      - `newChar`: The character to replace `oldChar` with.
    - Example:
      ```java
      String str = "Hello";
      String replacedStr = str.replace('l', 'w'); // Returns "Hewwo"
      ```

These are just a few of the many methods available in the String class in Java for manipulating strings.
