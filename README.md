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
Developed by: M UDHAYA SANKARAN
RegisterNumber: 212222110051
*/
def gcd():
    num1=int(input())
    num2=int(input())
    if num1<num2:
        smaller=num1
    else:
        smaller=num2
    for i in range(1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcdvalue=i
    print("GCD of two numbers is: {}".format(gcdvalue))
```

## Output:
![image](https://github.com/Udhayasankaran04/GCD-of-two-numbers/assets/119393933/7b9db507-fd62-4a35-aebd-d8122dd92bfd)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
