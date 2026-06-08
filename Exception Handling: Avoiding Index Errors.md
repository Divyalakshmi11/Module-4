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
Add code here
~~~
list1 = [10, 20, 30, 40]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
~~~
## Output

<img width="1548" height="985" alt="Screenshot 2025-10-20 145051" src="https://github.com/user-attachments/assets/6259f856-2422-4573-9384-3d983ed59bfc" />

## Result
The program successfully handles an IndexError, preventing the program from crashing when trying to access a non-existent index in a list.
