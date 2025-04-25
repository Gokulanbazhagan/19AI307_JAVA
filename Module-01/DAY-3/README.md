# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:

## Sourcecode.java:
 ```
/*
Program to implement a class & objects using Java
Developed by: gokularamanan K
RegisterNumber:  212222230040
*/


import java.util.Scanner;

public class MToN {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int m = scanner.nextInt();

        int n;

        if (m == 0) {
            System.out.println("Given number is Zero");
        } else  {
            System.out.println(m+" is Non-Zero");
          
        }


        scanner.close();
    }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/af20b32a-be6d-46f4-bc58-ddbd783385e5)


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

