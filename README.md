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
def sq():
    val1=int(input())
    val2=2
    for i in range(1,val1):
        val2=0.5*(val2+val1/val2)
    print("Square root of the number:",val2)
sq()
```

## Output:
![Screenshot 2023-11-20 134646](https://github.com/2005Mukesh/Square-root-of-a-number/assets/138849308/0b02fc62-e076-43d1-9515-a69560d2e142)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
