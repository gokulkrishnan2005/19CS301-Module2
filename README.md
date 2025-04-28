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
![image](https://github.com/gokulkrishnan2005/19CS301-Module2/blob/main/kk.png)

### RESULT
Thus the python program  to define a function that accepts 2 values and return its  modulo value has been implemented and executed successfully.

Exp.No:2(c)	BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS- z*56

### AIM
To write a python program using lambda function which takes z as a parameter and returns z*56 using python.
### ALGORITHM
Start

Read integer z from the user

Define a lambda function: product = lambda z: z * 56

Call the product function with input z

Print the result

End

### PROGRAM
```
z=int(input())
product=lambda z:z*56
print(product(z))
```
### OUTPUT
![image](https://github.com/gokulkrishnan2005/19CS301-Module2/blob/main/jj.png)


### RESULT
Thus the python program using lambda function which takes z as a parameter and returns z*56 using python has been implemented and executed successfully.


Exp.No:2(d)	LOOPING PATTERNS- PRINTING PATTERN

### AIM
To write a program to print inverted pyramid pattern with the same digit.
### ALGORITHM

Start

Read integer a from the user

Loop from i = a down to 1 (inclusive):

for i in range(a, 0, -1)

Inside the outer loop, loop from j = 0 to i - 1:

for j in range(0, i)

Print the value of a followed by a space (keep on same line)

Print a newline after the inner loop to move to the next row

End

### PROGRAM
```
a=int(input())
for i in range(a,0,-1):
    for j in range (0,i):
        print(a,end=" ")
    print()
```
### OUTPUT
![image](https://github.com/gokulkrishnan2005/19CS301-Module2/blob/main/oo.png)


 
### RESULT
Thus the python program to program to print inverted pyramid pattern with the same digit has been implemented and executed successfully.
























Exp.No:2(e)	SEB- COUNT DIGITS

### AIM
To write a python program to count the number of digits in a number. 
### ALGORITHM

Start

Read input a from the user (as a string)

Find the length of a using len(a) and store it in b

Print "The number of digits in the number are:", b

End

### PROGRAM
```
a=input()
b=len (a)
print("The number of digits in the number are:",b)
```
### OUTPUT
![image](https://github.com/gokulkrishnan2005/19CS301-Module2/blob/main/mm.png)

 

### RESULT
Thus the python program to count the number of digits in a number has been implemented and executed successfully.





