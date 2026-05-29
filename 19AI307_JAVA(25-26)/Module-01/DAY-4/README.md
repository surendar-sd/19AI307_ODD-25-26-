# Ex.No:1(D) ARRAYS

## QUESTION:

Write a Java program to find the index of a given element in an array


## AIM:


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.Read the element x whose index needs to be found.
4.Traverse the array from index 0 to n-1:
 If a[i] == x, print the index i and terminate the program.
5.If the loop finishes without a match, print "Element not found".
6.End the program.



## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: SURENDAR S D 
RegisterNumber: 212224110052
*/
```
## SOURCE CODE:
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int a[] = new int[n];
        for (int i = 0; i < n; i++) 
        {
        a[i] = sc.nextInt();
        }
        
        int x = sc.nextInt();
        for (int i = 0; i < n; i++) {
            if (a[i] == x) {
                System.out.println(i);
                return;
            }
            
        }
        System.out.println("Element not found");
        
    }
}
```

## OUTPUT:
<img width="684" height="727" alt="image" src="https://github.com/user-attachments/assets/34e923bf-98b2-40a2-8e6f-40ca3421e606" />




## RESULT:
