# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### DATE:                                                                            
### REGISTER NUMBER : 212221040062
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:
```
def is_prime(number):
    if not isnumber(number, int) or number < 2:
        return f"Invalid input: {number} is not a positive integer greater than 1."

    for i in range(2, int(number ** 0.5) + 1):
        if number % i == 0:
            return f"{number} is not a prime number."
    return f"{number} is a prime number."

print(is_prime(5))    
print(is_prime(4))   
print(is_prime(-5))   
print(is_prime(1))    
print(is_prime(2.5))  
print(is_prime(13))   
print(is_prime(20))   
print(is_prime(29))  
print(is_prime(97))   
print(is_prime(0))    

```

### Output:
![image](https://github.com/user-attachments/assets/5834cbcc-f59d-499f-bab1-89609c0a3226)





### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
