# Ex.No:1(E) Class and Object

## AIM:
To write a java program create a class named 'Distance' to add two distances in inch-feet by using third object. Get Input from user.

## ALGORITHM : 
1.Start

2.Create a class Distance with:

3.Two variables: feet and inches

4.In the main method:

  a. Create 3 objects: obj1, obj2, obj3

  b. Input feet and inches for obj1 and obj2

  c. Add feet and inches of obj1 and obj2 and store in obj3

  d. If inches ≥ 12, convert to feet:

5.Add extra feet to obj3.feet

6.Keep remaining inches in obj3.inches

7. Print the total distance

8.End



## PROGRAM:
## Sourcecode.java:
 ```
/*
Program to implement a Static Variable using Java
Developed by: Gokularamanan K
RegisterNumber:  212222230040
*/

import java.util.*;
public class Distance
{
    double feet,inches;
    public static void main(String[] args)
    {
       Scanner s = new Scanner(System.in);
     Distance obj3 = new Distance();
    Distance obj2 = new Distance();
   Distance obj1 = new Distance();
   obj1.feet=s.nextDouble();
  obj1.inches=s.nextDouble();
  obj2.feet=s.nextDouble();
  obj2.inches=s.nextDouble();
        obj3.feet=(obj1.feet+obj2.feet);
        obj3.inches=(obj1.inches+obj2.inches);
        System.out.println("Total Distance is "+obj3.feet+" feet and "+obj3.inches+" inches");        
    }
}
```




## OUTPUT:
![image](https://github.com/user-attachments/assets/08ff6d52-12a8-44d2-9828-3a2abb3c0bcb)



## RESULT:
Thus, the java program create a class named 'Distance' to add two distances in inch-feet by using third object. Get Input from user was correctly implemented and verified successfully. 

