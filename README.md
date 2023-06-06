# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: MANOJ G
RegisterNumber: 212222240060
*/
def newton_method(number,number_iters=100):
     a=float(number)
     for i in range(number_iters):
         number=0.5*(number+a/number)
     return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:
![241576014-c1c8c3af-cecd-42e2-8f38-589c974ece03](https://github.com/Danielmanoj/Square-root-of-a-number/assets/69635071/c5bc442a-8625-40ad-bdf6-6895ca346f34)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
