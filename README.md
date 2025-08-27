# Experiment-3
## PRIME NUMBER OR NOT

# Aim: Write a python program to check the number is prime or not and inspect for failures. 

# Algorithm
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
 - If the number is divisible by the current iteration value, return "Not Prime".
6. If the number is not divisible by any value from 2 to the square root, return "Prime".
7. Stop the program. 

## Program
```
num = int(input("Enter a number: "))

if num <= 1:
    print(f"{num} is NOT a Prime number")
else:
    is_prime = True
    for i in range(2, int(num**0.5) + 1):
        if num % i == 0:
            is_prime = False
            break

    if is_prime:
        print(f"{num} is a Prime number")
    else:
        print(f"{num} is NOT a Prime number")
```
## Output
<img width="692" height="174" alt="image" src="https://github.com/user-attachments/assets/bde20c37-28fc-4161-9aaf-54c945e4168e" />

## Result
Thus, the python program to check the number is prime or not and inspect for failures.
