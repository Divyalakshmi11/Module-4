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
