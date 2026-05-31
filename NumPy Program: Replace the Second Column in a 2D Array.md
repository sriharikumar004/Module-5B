# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy as np
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))
print("Enter elements of the array:")
arr = []
for i in range(rows):
    row = []
    for j in range(cols):
        element = int(input())
        row.append(element)
    arr.append(row)
array = np.array(arr)
print("Enter elements for the new column:")
new_column = []
for i in range(rows):
    value = int(input())
    new_column.append(value)
deleted_array = np.delete(array, 1, axis=1)
updated_array = np.insert(deleted_array, 1, new_column, axis=1)
print("Original Array:")
print(array)
print("\nUpdated Array:")
print(updated_array)
```
## Output
<img width="482" height="653" alt="image" src="https://github.com/user-attachments/assets/88dc401f-6844-4103-a271-b24ee1f4a925" />

## Result
The program is executed successfully.
