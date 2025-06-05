# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program

```python

import numpy as np

rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

arr = []
for i in range(rows):
    row = list(map(int, input(f"Enter row {i+1} elements: ").split()))
    arr.append(row)

a = np.array(arr)
sorted_a = np.sort(a, axis=0)

print("Original array:")
print(a)
print("Column-wise sorted array:")
print(sorted_a)

```

## Output

![image](https://github.com/user-attachments/assets/54d48099-95e1-4ba2-9a23-2fb2c812157a)

## Result

Thus implemented the python program to
