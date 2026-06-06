# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
l=[45,67,876,34,56]
res=sum(l)
print(res)
```

## Output

<img width="909" height="213" alt="image" src="https://github.com/user-attachments/assets/2cc2cb4a-4802-418b-ba28-055a71c0ce5b" />

## Result

The Python program that calculates the **sum of all elements** in a list is successfully executed.

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

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program

```
def remove(s):
    n=int(input())
    a=""
    for i in range(len(s)):
        if i!=n:
            a+=s[i]
    print(a)
s=input()
remove(s)
```

## Output

<img width="903" height="309" alt="image" src="https://github.com/user-attachments/assets/c1b8b43b-25e6-4142-a0b2-085e93d2cd6a" />

## Result

The Python program that accepts a string and removes the character at a specified index is successfully executed.

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
var='google'
var_rev=var[::-1]
if var==var_rev:
    print("The string is a Palindrome.")
else:
    print("The string is not a Palindrome.")
```

## Output

<img width="907" height="210" alt="image" src="https://github.com/user-attachments/assets/ab5ffb3f-fbfb-4a2f-992a-9e1b180f2884" />

## Result

The Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is successfully developed and executed.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

```
x=(1,'a',7,'u',6,'B',8)
flag_n=False
flag_8=False
for i in x:
    if i=='n':
        flag_n=True
    if i==8:
        flag_8=True
if flag_n:
    print("n is present in the string")
else:
    print("n is not present in the string")
if flag_8:
    print("8 is present in the tuple")
else:
    print("8 is not present in the tuple")
```

## Output

<img width="887" height="249" alt="image" src="https://github.com/user-attachments/assets/c61c227e-89b7-4caf-8860-897750811101" />

## Result

The Python program that checks if the element `'n'` and the element `8` exist within a given tuple is successfully developed and executed.
