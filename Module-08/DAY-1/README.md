# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To implement a Java Program to write a String in a file "testout.txt" using FileOutputStream

## ALGORITHM :
1.  Define the string "Welcome to Saveetha" and convert it to a byte array b using getBytes().
2.	Use Scanner to prompt the user for start (starting index) and length (number of bytes) to write from the string.
3.	Open testout.txt using FileOutputStream, and write the specified portion of b from the start index for length bytes, then close the output stream.
4.	Open testout.txt using FileInputStream, read its contents byte-by-byte, convert each byte to a character, and print it to display the file's content.
5.	Use file.delete() to delete testout.txt.
6.	Attempt to read the deleted file, which triggers a FileNotFoundException as the file no longer exists.


## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:

```
 
             try
             {
                OutputStream f=new FileOutputStream("testout.txt",true);
                String s="Welcome to Saveetha";
                byte [] b=s.getBytes();
                f.write(b);
                f.close();
                System.out.println("Successfully Completed");

               
  
                }
                catch(Exception e){System.out.println(e);}
```





## OUTPUT:


![image](https://github.com/user-attachments/assets/7af46932-5bc5-4a09-8d3d-f46a652e3e95)


## RESULT:
Thus the implementation of a Java Program to write a String in a file "testout.txt" using FileOutputStream was executed and verified successfully

