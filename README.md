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
def gcd():
    if (n1>n2):
        smaller=n2
    else:
        smaller=n1
    for i in range (1,smaller+1):
        if(n1%i==0 and n2%i==0):
           gcd=i
    print("GCD of two numbers is:",gcd)
n1=int(input())
n2=int(input())
```
## Output:

![Screenshot 2023-11-28 173822](https://github.com/Thrishendra/GCD-of-two-numbers/assets/145742464/0254f7d4-ffd9-434b-80cd-c2b7db928782)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
