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
```
import numpy as np

rows = int(input())
cols = int(input())

elements = []
for i in range(rows):
    row = list(map(int, input().split()))
    elements.append(row)

arr = np.array(elements)
print("\nOriginal Array:")
print(arr)

sorted_arr = np.sort(arr, axis=0)
print("Column-wise Sorted Array:")
print(sorted_arr)
```
## Output
![image](https://github.com/user-attachments/assets/5587b882-e928-4f0a-9443-d3c5def1c014)


## Result
Thus, the program is verified successfully.
