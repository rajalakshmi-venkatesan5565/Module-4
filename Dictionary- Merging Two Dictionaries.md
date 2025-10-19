## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}


merged_dict = {**dict1, **dict2}

print("Merged Dictionary:", merged_dict)
```
## Output
<img width="1042" height="467" alt="Screenshot 2025-10-19 105327" src="https://github.com/user-attachments/assets/d899a1f2-51de-4cae-a243-8544db6d3eb3" />

## Result
the  Python program that merges **two dictionaries** and combines their key-value pairs is executed successfully.
