# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```py

list1 = [10, 20, 30, 40]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```
## Output
<img width="469" height="242" alt="image" src="https://github.com/user-attachments/assets/e5cbd8ad-ef94-41fa-acf6-a71eaae41b8d" />


## Result
The Python program was executed successfully, and the IndexError was handled using a try-except block. Instead of crashing, the program displayed a custom message indicating that the index is out of range.
