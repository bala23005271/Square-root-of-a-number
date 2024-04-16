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
# Program to find the square root for the given number(newton's method) using function.
# Developed by: bala murugan s
# RegisterNumber : 212223230027
def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp))

```

## Output:
![image](https://github.com/bala23005271/Square-root-of-a-number/assets/155039753/37f33e6f-aafa-48dd-8da7-9d26f2136eef)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
