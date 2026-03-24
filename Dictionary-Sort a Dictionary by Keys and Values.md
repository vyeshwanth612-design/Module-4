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
```py

d = {'b': 2, 'a': 1, 'd': 4, 'c': 3}

sorted_keys = dict(sorted(d.items()))

sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original dictionary:", d)
print("Sorted by keys:", sorted_keys)
print("Sorted by values:", sorted_values)
```
## Sample Output
<img width="688" height="259" alt="image" src="https://github.com/user-attachments/assets/56f46720-d2ee-406d-9b4f-699dcd2bb80d" />


## Result
The Python program was executed successfully, and the dictionary was sorted both by keys and by values in alphabetical/numerical order. The sorted results were displayed correctly.

