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
Developed by: JEECIKASRINA M
RegisterNumber:  23013947
def root(x,b):
    y=0.5*(x+b/x)
    if y==x:
        return y
    else:
        return root(y,b)
b=int(input())
res=root(b,b)
print("Square root of the number:",res)
```

## Output:
![image](https://github.com/Jeecikasrina23013947/Square-root-of-a-number/assets/148515300/1f3e29ed-93db-44f8-aec7-93b3032e14a1)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
