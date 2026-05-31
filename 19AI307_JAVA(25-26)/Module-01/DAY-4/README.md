# Ex.No:1(D) ARRAYS

## QUESTION:
 Write a Java Program to Find the Average of Array Elements.

## AIM:

To write a Java Program to Find the Average of Array Elements.



## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Start the program and read the number of elements n from the user.
4. Create an integer array of size n and initialize sum = 0.
5. Use a loop to read n elements and store them in the array while adding each element to sum.
6. Calculate the average using average = (float) sum / n.
7. Display the average value formatted to two decimal places and stop the program.
8. End the program.

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: HARISH P K
RegisterNumber:  212224040104
*/
```

## SOURCE CODE:

```java
import java.util.Scanner;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int arr[] = new int[n];
        int sum=0;
        for (int i=0;i<n;i++)
        {
            arr[i] = sc.nextInt();
            sum+=arr[i];
        }
        float res = (float) sum/n;
        System.out.printf("The average of elements is %.2f",res);
        
    }
}
```

## OUTPUT:
<img width="1014" height="578" alt="image" src="https://github.com/user-attachments/assets/54e01383-256c-4da1-928f-03e30a96ed99" />



## RESULT:
Thus, the Java Program to Find the Average of Array Elements has been executed Successfully.
