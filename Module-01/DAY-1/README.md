# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and integer variable 'rollno'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a integer variable rollno and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'rollno' variables of the 'obj' object
9.	End



## PROGRAM:
## Sourcecode.java:
 ```
///
Program to implement a class & objects using Java
Developed by: Gokularamanan K
RegisterNumber: 212222230040
///

class Test {
    public static void main(String[] args) {
       Student obj = new Student();
        obj.name="John";
        obj.rollno=15;   
        System.out.println(obj.name+" "+obj.rollno);
    }   
}

class Student {
        String name;
        int rollno;
}


```

## OUTPUT:

John 15




## RESULT:
Thus, the class named 'Student' with String variable 'name' and int variable 'rollno' was created successfully.
