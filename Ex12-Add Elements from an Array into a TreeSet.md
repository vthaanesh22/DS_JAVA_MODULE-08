# Ex12 Add Elements from an Array into a TreeSet
# Date: 28/02/2026

## AIM:
To write a Java program that adds elements from an array into a TreeSet and displays the elements in sorted order.
## Algorithm
1. Start the program.
2. Create an array containing integer elements.
3. Create a TreeSet object.
4. Add all elements of the array to the TreeSet using a loop or Collections method.
5. Display the elements of the TreeSet.
6. Stop the program.

## Program:
```
/*
Program that adds elements from an array into a TreeSet and displays the elements in sorted order.
Developed by: Thaanesh V
RegisterNumber: 212223230228
*/
import java.util.*;

public class ArrayToTreeSet
 {
    public static void main(String[] args)
{

        int[] arr = {40, 10, 50, 30, 20};
        TreeSet<Integer> set = new TreeSet<Integer>();
        for (int num : arr) {
            set.add(num);
        }
        System.out.println("Elements in TreeSet (Sorted Order): " + set);
    }
}

```

## Output:

<img width="624" height="436" alt="image" src="https://github.com/user-attachments/assets/869f72c0-2cfe-4e38-a11e-669968f0a796" />



## Result:
The program successfully adds elements from an array into a TreeSet.
