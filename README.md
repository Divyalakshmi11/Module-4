# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
~~~
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print("Area of the circle:", area)

radius = float(input("Enter the radius of the circle: "))
obj = cse()
obj.mech(radius)
~~~

## Output


<img width="1564" height="978" alt="Screenshot 2025-10-20 144727" src="https://github.com/user-attachments/assets/38d33d4c-ad0f-4ae7-8a36-17f940fa0b05" />
## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

~~~
def merge(dict1, dict2):
    merged = {**dict1, **dict2}
    return merged

dict1 = {'a': 10, 'b': 20}
dict2 = {'b': 30, 'c': 40}

result = merge(dict1, dict2)
print("Merged dictionary:", result)
~~~
## Output

<img width="1552" height="987" alt="Screenshot 2025-10-20 144840" src="https://github.com/user-attachments/assets/3f588311-4372-4108-a5e3-92f32d992bd0" />

## Result
The program successfully merges two dictionaries, combining all key-value pairs. If a key exists in both, the value from the second dictionary overwrites the first.

## Result
The program successfully calculates the area of a circle for any radius entered by the user using a class and method.

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
~~~
dictionary = {'banana': 3, 'apple': 4, 'cherry': 2}
sorted_by_keys = dict(sorted(dictionary.items()))
sorted_by_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))

print("Original dictionary:", dictionary)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)
~~~

## Sample Output

<img width="1543" height="988" alt="Screenshot 2025-10-20 144931" src="https://github.com/user-attachments/assets/c202d2ed-6b58-4688-bd4d-5fa224175e82" />

## Result
The program successfully sorts a dictionary's:

Keys in alphabetical order Values in alphabetical order.

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
