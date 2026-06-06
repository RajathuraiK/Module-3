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
