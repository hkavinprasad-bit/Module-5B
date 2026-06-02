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

# Get number of rows and columns
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

# Input array elements
print("Enter the array elements:")
arr = np.array([[int(input()) for j in range(cols)] for i in range(rows)])

# Sort each column in ascending order
sorted_arr = np.sort(arr, axis=0)

# Display output
print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)
```
## Output
<img width="496" height="381" alt="WhatsApp Image 2026-06-02 at 9 16 41 AM" src="https://github.com/user-attachments/assets/52b1c535-f6fc-4504-9e96-64e06a868e0b" />

## Result
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is successfully.
