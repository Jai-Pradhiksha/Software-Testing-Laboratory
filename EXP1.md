# Ex.No: 1 Write programs in Python Language to demonstrate the working of following constructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212221040062

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
```
def display(): 
    start=input("Enter a positive value for START: ")
    if start.isnumeric():
        end=input("Enter a positive value for END: ") 
        if end.isnumeric(): 
            while True: 
                start=int(start) 
                end=int(end) 
                print(start,end=' ') 
                if start<end: 
                    start+=1 
                else: 
                    break 
        else: 
            print("The value",end,"is not a positive number.")
    else: 
        print("The value",start,"is not a positive number.")
display()

```













### Output:
```
Python 3.12.4 (tags/v3.12.4:8e8a4ba, Jun  6 2024, 19:30:16) [MSC v.1940 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.

= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: 1
Enter a positive value for END: 4
1 2 3 4 

= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: -10
The value -10 is not a positive number.
5
5

= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: 5
Enter a positive value for END: -10
The value -10 is not a positive number.

= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: hello
The value hello is not a positive number.

= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: 5
Enter a positive value for END: 3
5 

= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: 5
Enter a positive value for END: 5
5 
>>> 
= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: jai
The value jai is not a positive number.
>>> 
= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: 
The value  is not a positive number.
>>> 
= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: 0
Enter a positive value for END: 
The value  is not a positive number.
>>> 
= RESTART: C:/Users/Jai Pradhiksha/AppData/Local/Programs/Python/Python312/STL/exp1-1.py
Enter a positive value for START: 4
Enter a positive value for END: #
The value # is not a positive number.

```






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


