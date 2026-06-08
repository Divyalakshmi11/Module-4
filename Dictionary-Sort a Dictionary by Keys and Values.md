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
