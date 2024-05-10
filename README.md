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
#developed by:r.sivakumar.R
# reg no:212223230209 



def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
       a,b=b,a%b
    print("GCD of two numbers is:",a)
```

## Output:
<img width="442" alt="Screenshot 2024-03-06 114442" src="https://github.com/SIVAmech123/GCD-of-two-numbers/assets/151629067/ed4a0ce8-ec2a-4e68-959b-ce25b28c6c2a">

<img width="468" alt="Screenshot 2024-03-06 114500" src="https://github.com/SIVAmech123/GCD-of-two-numbers/assets/151629067/e0ee6da4-a8b9-417a-b62a-ca7b13b0c7a4">


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
