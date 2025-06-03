# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: JANANI S
RegisterNumber:  212222230049
*/
```

## Sourcecode.java:
```
import java.util.*;
import java.util.Scanner;
class s1{
    void Oddsum(int number)
    {
	int i = 1, sum = 0;
	while(i <= number) 
        {
            sum += i;
            i++;
        }
 
    System.out.println("Sum = " + sum);
    } 

 
}

public class Odd_sum{
	public static void main(String args[])
	{
	   int number;  
      
      Scanner sc = new Scanner(System.in);
      number=sc.nextInt();
      s1 obj=new s1();
      obj.Oddsum(number);
	}
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/fae089e9-06a9-4afc-89ef-1c52fda61edc)



## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
