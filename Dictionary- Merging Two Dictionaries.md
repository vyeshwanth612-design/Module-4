## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```py

dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

def merge(d1, d2):
    return {**d1, **d2}

result = merge(dict1, dict2)

print("Merged dictionary:", result)
```
## Output
<img width="641" height="255" alt="image" src="https://github.com/user-attachments/assets/97ab2299-2606-45b0-9719-23fc43ff0ef3" />


## Result
The Python program was executed successfully, and the two dictionaries were merged using the unpacking (**) operator. The resulting dictionary correctly combined key-value pairs, with values from the second dictionary overriding duplicates.
