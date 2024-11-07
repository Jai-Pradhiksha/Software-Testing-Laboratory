# Ex.No: 5 To search a given element is present in the list using Binary search
### DATE:                                                                            
### REGISTER NUMBER : 212221040062
### AIM: 
Write a program in Python language to search a given element is present in the list using Binary search. Introspect the causes for its failure and write down the possible reasons for its failure.

### Algorithm:
1. Input: A sorted list arr and a target element to search for.
2. Initialize:
3. Set left to the start index (0).
4. Set right to the end index (len(arr) - 1).
5. Loop while left is less than or equal to right:
6. Calculate the midpoint mid as (left + right) // 2.
7. If arr[mid] equals target, return the index mid.
8. If arr[mid] is less than target, set left to mid + 1.
9. If arr[mid] is greater than target, set right to mid - 1.
10. Return "not found" if the target is not in the list.


### Program:
```
def binary_search(arr, target):
    if not isinstance(arr, list) or not all(isinstance(x, (int, float)) for x in arr):
        return "Invalid input: arr should be a list of numbers."
    if not isinstance(target, (int, float)):
        return "Invalid input: target should be a number."
    if arr != sorted(arr):
        return "Invalid input: arr should be sorted in ascending order."
    
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return f"{target} found at index {mid}"
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return f"{target} not found in the list"

print(binary_search([1, 3, 5, 7, 9], 7))          
print(binary_search([1, 3, 5, 7, 9], 4))           
print(binary_search([2, 4, 6, 8, 10], 10))         
print(binary_search([2, 4, 6, 8, 10], -1))        
print(binary_search([1, 3, 5, 7, 9, 11], 11))     
print(binary_search([], 3))                        
print(binary_search([1, 3, 5, 7, 9], 'a'))        
print(binary_search("12345", 3))                  
print(binary_search([1, 5, 3, 7, 9], 3))          
print(binary_search([1, 2, 3, 4, 5], 0))          

```












### Output:
![image](https://github.com/user-attachments/assets/a6a504c3-2604-4f3e-a6bd-bcb22d166c5a)



### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.

