# Ex.No:7(E)  POLYMORPHISM

## AIM:
To implement method overloading in Java to calculate the sum of two and three numbers demonstrating compile-time polymorphism
## ALGORITHM :
1.	Start the program.
2.	Create a class named SumExample.
3.	Inside the class, define:
     a.	A method sum(int a, int b) to calculate the sum of two numbers.
     b.	An overloaded method sum(int a, int b, int c) to calculate the sum of three numbers.
4.	In the main() method:
      a.	Create an object of the SumExample class.
      b.	Call both versions of the sum() method with appropriate arguments.
      c.	Print the results.
5.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: JANANI.S
RegisterNumber: 212222230049 
*/
```

## Sourcecode.java:

```

import java.util.*;
class Calculation{
  
 void sum(int a,int b)
  {
     System.out.println(a+b);
  }
  void sum(int a,int b,int c){
     System.out.println(a+b+c);
   }
  
}


public class HelloWorld{

     public static void main(String []args)
     {
       
  Calculation obj=new Calculation();
  Scanner sc=new Scanner(System.in);
  int a = sc.nextInt();
  int b=sc.nextInt();
  int c=sc.nextInt();
  obj.sum(a,b);
  obj.sum(a,b,c);
}
}
```


## OUTPUT:


![image](https://github.com/user-attachments/assets/03904b3c-93b8-4e46-883c-28db6ffb81cb)


## RESULT:

Thus the  java program successfully demonstrates method overloading, showing compile-time polymorphism by calculating the sum of two and three numbers using methods with the same name but different parameter lists..


