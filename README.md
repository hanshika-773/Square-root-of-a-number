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
Developed by: Hanshika Varthini R
RegisterNumber:  212223240046

def newton_sqrt(number, tolerance=1e-10, max_iterations=1000):

    x = number
    for _ in range(max_iterations):
        next_x = 0.5 * (x + number / x)
        if abs(next_x - x) < tolerance:
            return next_x
        x = next_x
number=int(input())
result = newton_sqrt(number)
print(f"Square root of the number: {result}")

*/
```

## Output:
![Screenshot 2024-10-15 204805](https://github.com/user-attachments/assets/14210ef8-97c9-4acd-8719-3f18659dbdf5)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
