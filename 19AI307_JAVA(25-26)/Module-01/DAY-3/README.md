# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:

Display Factors of a Number

## AIM:
To write a Java program that reads an integer from the user and displays all the factors of the given number.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Loop from 1 to n and check if each number i divides n exactly (i.e., n % i == 0).
4. If yes, print i as a factor.
5. Continue the loop until all factors are printed.
6. End the program.


## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: HARISH P K
RegisterNumber:  212224040104
*/
```

## SOURCE CODE:

```java
import java.util.Scanner;

public class Factors {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();

        System.out.print("Factors: ");
        for (int i = 1; i <= n; i++) {
            if (n % i == 0) { 
                System.out.print(i + " ");
            }
        }
    }
}
```

## OUTPUT:

<img width="783" height="324" alt="image" src="https://github.com/user-attachments/assets/e888c960-a309-4646-bf5b-aa034c95e833" />


## RESULT:
Therefore, the program successfully reads a number from the user and computes its factors.

