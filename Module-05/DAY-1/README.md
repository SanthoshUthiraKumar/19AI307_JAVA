# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the employee and use the encapsulation concepts

## ALGORITHM :
1.  Start the program
2.	Define class `Employee`:
-	a) Declare two private `String` variables: `name1` and `name2`
-	b) Define `setname(String n1)` method to set `name1` to `n1`
-	c) Define `setname2(String n2)` method to set `name2` to `n2`
-	d) Define `get1()` method to return `name1`
-	e) Define `get2()` method to return `name2`
3.	Define `Main` class with `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read `name1` and `name2` from user input
-	c) Create ` Employee ` object `hl`
-	d) Use `hl.setname(name1)` and `hl.setname2(name2)` to set the names
-	e) Print the values of `hl.get1()` and `hl.get2()`
4.	End





## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: Santhosh U
RegisterNumber:  212222240092
*/
```

```
import java.util.*;
class add
{
    private int a,b;
    public void sno1(int x)
    {
        a=x;
    }
    public void sno2(int y)
    {
        b=y;
    }
    void sum()
    {
        int out=a*b;
        System.out.print(out);
    }
}
public class ss{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        add obj=new add();
        obj.sno1(sc.nextInt());
        obj.sno2(sc.nextInt());
        obj.sum();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/c5d1e44d-5c1d-49a5-872c-11c5ca75a7d3)

## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
