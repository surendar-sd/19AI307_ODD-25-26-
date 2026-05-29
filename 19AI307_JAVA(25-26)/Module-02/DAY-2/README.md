# Ex.No:2(B) METHODS

## QUESTION:

Write a method int cube(int x) that calls a method int square(int x) internally to calculate the cube as x * square(x).


## AIM:

To write a Java program that defines a method cube(int x) which internally calls the method square(int x) to compute the cube of a number.


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create an object of the demo class.
4.Call the cube() method using the object and print the result.
5.End the program.





## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: SURENDAR S D 
RegisterNumber: 212224110052 
*/
```

## SOURCE CODE:

```
import java.util.*;
class demo
{
    public int square(int n)
    {
        return n*n;
    }
    public int cube(int n)
    {
        return n*square(n);
    }
    
}
public class main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        demo d=new demo();
        System.out.println(d.cube(n));
    }
}
```







## OUTPUT:

<img width="487" height="300" alt="image" src="https://github.com/user-attachments/assets/f4ba92a4-57a9-45aa-add2-e51352f2c4c0" />


## RESULT:

Therefore the program successfully computes the cube of a number by internally using the square method.
