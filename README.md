# Lab: 6.0.6

**Objective:**

- Understand the concept and importance of Advanced Array Methods in Java development.
- Learn how to implement Advanced Array Methods using Java's Arrays utility class.
- Explore practical applications of Advanced Array Methods in real-world Java projects.
- Identify common pitfalls and best practices when working with Advanced Array Methods.
- Gain hands-on experience with a complete Java example that demonstrates Advanced Array Methods.

**Prerequisites:**

- Solid understanding of Java programming basics.
- Familiarity with arrays and basic array operations in Java.

**What You'll Achieve:**

- Develop a solid understanding of Advanced Array Methods in Java.
- Implement practical examples that can be applied in real-world scenarios.
- Enhance your skills in array manipulation and data processing.

**Assignment Details**

In the main method of the `AdvancedArrayMethods` class, implement the following operations:

1. Create an array of integers with at least 20 elements, including some duplicates. 
2. Use `Arrays.sort()` to sort the array and print the sorted array. 
3. Use `Arrays.binarySearch()` to find the index of a specific element in the sorted array. 
4. Use `Arrays.fill()` to replace a portion of the array with a specific value. 
5. Create a copy of the array using `Arrays.copyOf()` and demonstrate deep copy vs shallow copy. 
6. Use `Arrays.equals()` to compare two arrays. 
7. Convert the array to a List using `Arrays.asList()` and demonstrate its use. 
8. Use loops to perform the following operations:
   - Find the sum of all elements.
   - Find the average of all elements.
   - Filter the array to only even numbers and collect them into a new array.
   - Square each element and collect the results into a new array.
9. Print the results of each operation.

**Example Output**

```
Original array: [5, 2, 8, 1, 9, 3, 7, 4, 6, 10, 5, 2, 8, 1, 9, 3, 7, 4, 6, 10]
Sorted array: [1, 1, 2, 2, 3, 3, 4, 4, 5, 5, 6, 6, 7, 7, 8, 8, 9, 9, 10, 10]
Index of 7: 12
Array after fill: [1, 1, 2, 2, 3, 99, 99, 99, 99, 99, 6, 6, 7, 7, 8, 8, 9, 9, 10, 10]
Arrays are equal: true
Sum of all elements: 100
Average of all elements: 5.0
Even numbers: [2, 2, 4, 4, 6, 6, 8, 8, 10, 10]
Squared elements: [1, 1, 4, 4, 9, 9801, 9801, 9801, 9801, 9801, 36, 36, 49, 49, 64, 64, 81, 81, 100, 100]
```

**Starter Code**

The `AdvancedArrayMethods.java` file contains the following starter code:

```java
package academy.javapro.lab;

import java.util.Arrays;
import java.util.List;

public class AdvancedArrayMethods {
    public static void main(String[] args) {
        // TODO: Create an array of integers

        // TODO: Implement the required operations

        // TODO: Print results
    }
}

```

**Hints**

- Use `System.out.println(Arrays.toString(array))` to print arrays.
- Remember that `Arrays.binarySearch(`) requires a sorted array.
- When using `Arrays.fill()`, be careful with the start and end indices.
- For filtering and transforming arrays, you may need to use temporary arrays or lists to store intermediate results.
- When creating new arrays for filtered or transformed results, consider using `ArrayList` for dynamic sizing, then convert to an array if needed.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required operations in the main method of `AdvancedArrayMethods.java`
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.