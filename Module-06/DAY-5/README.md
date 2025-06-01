# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To write a Java program using multiple inheritance through interfaces to read student details and marks, calculate the average, and display the mark sheet.

## ALGORITHM :

1.	Start the program.
2.	Create interface Student:
a.	Declare methods to read name and rollno.
3.	Create interface Studentdet:
a.	Declare a method to read marks of 6 subjects and calculate the average.
b.	Create a class Studentdetails that implements both interfaces:
c.	Define variables for name, roll number, marks array, and average.
4.	Implement all methods from the interfaces.
a.	Create a display() method to show student details and average.
5.	In main() method:
a.	Create an object of Studentdetails.
b.	Call the methods to get input and display results.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: Santhosh U
RegisterNumber:  212222240092
*/
```

## Sourcecode.java:

```
import java.util.*;
class Number{
    int num1=10,num2=5,result;
    public void display(String ope){
        System.out.println(ope+" of 2 values "+result);
    }
}
class Addition extends Number{
    public void add(){
        result=num1+num2;
    }
}
class Subtraction extends Number{
    public void sub(){
        result=num1-num2;
    }
}
public class Main{
    public static void main(String[] args){
        Addition obj=new Addition();
        obj.add();
        obj.display("Addition");
        Subtraction obj1=new Subtraction();
        obj1.sub();
        obj1.display("Subtraction");
    }
}
```





## OUTPUT:

![image](https://github.com/user-attachments/assets/536d3254-968a-44b6-b7a4-6c4992a0b7cd)

## RESULT:

Thus, the java program demonstrates multiple inheritance using interfaces and successfully displays the mark sheet of a student by collecting personal and academic data. 
