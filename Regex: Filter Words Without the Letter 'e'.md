# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program

```
import re
l1=[]
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
pattern = r"e"
for i in items:
    if not re.search(pattern, i):
        l1.append(i)
print(l1)
```

## Output

<img width="908" height="262" alt="image" src="https://github.com/user-attachments/assets/0019f458-960b-4368-b1b5-a062f46416e1" />

## Result

The Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is successfully executed.
