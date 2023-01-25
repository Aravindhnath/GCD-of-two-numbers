# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Aravindhnath T R
RegisterNumber: 22009024 
*/
```
```
def gcd():
    x,y=int(input()),int(input())
    if x>y:
        smaller=y
    else:
        smaller=x
    for i in range(1,smaller+1):
        if(x%i==0 and y%i==0):
            hvf=i
    print("GCD of two numbers is:",hvf)
```
    
## Output:
![Screenshot 2023-01-26 002423](https://user-images.githubusercontent.com/118790841/214657027-d8541ab3-bffa-43ee-b2c5-5a6ca7151aea.png)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
