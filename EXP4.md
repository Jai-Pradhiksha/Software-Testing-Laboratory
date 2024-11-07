# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE:                                                                            
### REGISTER NUMBER : 212221040062
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:
```
def is_armstrong(number):
    if not isinstance(number, int) or number < 0:
        return f"Invalid input: {number} is not a non-negative integer."
    num_str = str(number)
    power = len(num_str)
    armstrong_sum = sum(int(digit) ** power for digit in num_str)
    if armstrong_sum == number:
        return f"{number} is an Armstrong number."
    else:
        return f"{number} is not an Armstrong number."

print(is_armstrong(153))
print(is_armstrong(370))
print(is_armstrong(9474))
print(is_armstrong(123))
print(is_armstrong(-153))
print(is_armstrong(0))
print(is_armstrong(1))
print(is_armstrong(407))
print(is_armstrong(9475))
print(is_armstrong(100))

```












### Output:

![image](https://github.com/user-attachments/assets/efe86e84-f24b-401a-90be-20254fcb0a49)





### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


