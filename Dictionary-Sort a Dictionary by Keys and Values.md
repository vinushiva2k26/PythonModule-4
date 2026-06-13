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

```python
dictionary = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'green',
    'orange': 'orange'
}

# Sort by keys
sorted_keys = dict(sorted(dictionary.items()))

# Sort by values
sorted_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))

print("Original Dictionary:", dictionary)
print("Sorted by Keys:", sorted_keys)
print("Sorted by Values:", sorted_values)
```

## Output

```text
Original Dictionary: {'banana': 'yellow', 'apple': 'red', 'grape': 'green', 'orange': 'orange'}

Sorted by Keys: {'apple': 'red', 'banana': 'yellow', 'grape': 'green', 'orange': 'orange'}

Sorted by Values: {'grape': 'green', 'orange': 'orange', 'apple': 'red', 'banana': 'yellow'}
```

## Result

Thus, the Python program was successfully executed to sort a dictionary by keys and values in alphabetical order.

