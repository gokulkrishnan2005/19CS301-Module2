# 19CS301-Module2
Exp.No:2(a)	ITERATIVE STATEMENTS- PRINTING DIVISIBLE BY 11 NUMBERS
### AIM
To create a  print  numbers  range from M to N (including M and N values) divisible by 11 in reverse order.
### ALGORITHM

Start

Read integer a from the user.

Read integer b from the user.

Loop from i = b down to a (inclusive):

Use a for loop: for i in range(b, a - 1, -1)

Check if the current number i is divisible by 11:

If i % 11 == 0, then:

Print i

End

### PROGRAM
```
a=int(input())
b=int(input())
for i in range(b,a-1,-1):
    if i%11==0:
        print(i)
```
### OUTPUT
![image](https://github.com/gokulkrishnan2005/19CS301-Module2/blob/main/LL.png)

 
### RESULT
Thus the python program for print  numbers  range from M to N (including M and N values) divisible by 11 in reverse order has been implemented and executed successfully.

Exp.No:2(b)	FUNCTIONS-MODULO VALUE.

### AIM
To write a Python program to define a function that accepts 2 values and return its  modulo value  
### ALGORITHM

Start

Read integer a from the user

Read integer b from the user

Compute the remainder: c = a % b

Print the result as "modulo is", c

End


### PROGRAM
```
def result (a,b):
    c= a%b
    print ("modulo is",c)

a=int(input())
b=int(input())
```

### OUTPUT
![image](https://github.com/user-attachments/assets/cc9562f9-e9f5-4989-82fc-6fcea0ec493f)

### RESULT
Thus the python program to check if a number is a perfect number or not has been implemented and executed successfully.

Exp.No:2(c)	BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS- RELATING TWO NUMBERS

### AIM
To write a python program to check the relation between them. That is if one number is greater or equal or lesser than another number using the lambda function.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Use eval() to get the two numbers (num1 and num2) from the user.

Step 3:	 Define a lambda function res that takes two arguments x and y

Step 4:	 The lambda function compares the numbers and prints which one is smaller: If x > y, it prints num2 is smaller than num1. Otherwise, it prints num1 is smaller than num2.

Step 5:	 Call the res Function: Pass num1 and num2 to the lambda function to perform the comparison.

Step 6:	 Terminate the program.
### PROGRAM
```num1=eval(input())
num2=eval(input())
max=lambda x,y: print(f"{num2} is smaller than {num1}") if x>y else print(f"{num1} is smaller than {num2}")![image](https://github.com/user-attachments/assets/4a3ccdb3-e831-41b8-b783-4f58c664521e)

max(num1,num2)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/d6767aa8-b158-4f19-83f6-af03322a5b9d)


### RESULT
Thus the python program to check a relationship between two numbers has been implemented and executed successfully.


Exp.No:2(d)	LOOPING PATTERNS- PRINTING PATTERN

### AIM
To write a python program to print the triangular star pattern.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Read the integer n from the user using input(). This will determine the number of rows in the pattern.

Step 3:	 Initialize a variable i = 0. This will be used to control the number of spaces before the stars.

Step 4:	 Loop through rows from 0 to n-1 (this will iterate n times to print the required rows).

Step 5:	  For each row, calculate the number of spaces before the stars. 

Step 6:	 The formula for the number of spaces is ((n - rows - 1) * 2) + i. 

Step 7:	 Print the spaces (" ") using the print(" ", end="") statement. 

Step 8:	 Increment i by 1 after each row.

Step 9:	 For each row, print the stars. The number of stars for each row is equal to rows + 1. Print the stars with print("*", end=" ") to separate them with two spaces.

Step 10:	 After printing each row's stars, print a newline to move to the next row using print("").

Step 11:	 Terminate the program.
### PROGRAM
```n=int(input())
i=0
for rows in range(0,n):
    for cols in range(((n-rows-1)*2)+i):
        print(" ",end="")
    i+=1
    for star in range(rows+1):
        print("*",end="  ")
    print("")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/97a7d6f9-97f1-44e6-a8b1-2c110a717d1c)


 
### RESULT
Thus the python program to print the triangular start pattern has been implemented and executed successfully.
























Exp.No:2(e)	SEB- COMPUTING POWER

### AIM
To write a python Program to compute the power of the given number using appropriate built -in function .
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Input the base number (base) from the user.

Step 3:	 Input the exponent number (exp) from the user.

Step 4:	 Use the built-in pow() function to compute the  base raised to the power of exp.

Step 5:	 Print the result using the print() function, displaying the power of the given number in a formatted manner.

Step 6:	 Terminate the program.
### PROGRAM
```base=int(input())
exp=int(input())
res=pow(base,exp)
print(f"Power of the given number is: {res}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/f0c61287-b7a6-4c76-908d-396f4104d75b)

 

### RESULT
Thus the python program to compute the power using builtin function has been implemented and executed successfully.





