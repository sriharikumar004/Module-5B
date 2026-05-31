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

arr = np.array([[9, 3, 7],[2, 8, 1],[5, 6, 4]])
sorted_arr = np.sort(arr, axis=0)
print("Original Array:")
print(arr)
print("\nColumn-wise Sorted Array:")
print(sorted_arr)
```
## Output
<img width="498" height="398" alt="image" src="https://github.com/user-attachments/assets/38a0c502-0f7e-4972-ac93-aa6be3da227f" />

## Result
The program is executed successfully.
