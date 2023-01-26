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
```python
Program to find the square root for the given number(newton's method) using function.
Developed by: s.thirisha
RegisterNumber: 22001920
def squareroot(num1,iterum):
    num2=float(num1)
    for i in range(iterum):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)    
    #return num1
num1=int(input())
iterum=100
squareroot(num1,iterum)
```
## Output:
![Screenshot_20230119_134933](https://user-images.githubusercontent.com/120380280/213749615-82e3c149-cd50-4624-b601-c983ee31c036.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
