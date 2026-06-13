# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program

```python
count = 0

file = open("story.txt", "r")

for line in file:
    if line[0] != 'T':
        count += 1

print(count)

file.close()
```

## Output

```text
3
```

## Result

Thus, the Python program was successfully executed to count the number of lines in the file that do not start with the alphabet 'T'.
