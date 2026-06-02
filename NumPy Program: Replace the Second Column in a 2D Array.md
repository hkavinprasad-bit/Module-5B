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

# Get rows and columns
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

# Input original array
print("Enter array elements:")
arr = np.array([[int(input()) for j in range(cols)] for i in range(rows)])

# Input new column
print("Enter elements of the new column:")
new_col = np.array([int(input()) for i in range(rows)])

# Delete second column (index 1)
arr = np.delete(arr, 1, axis=1)

# Insert new column at second position
arr = np.insert(arr, 1, new_col, axis=1)

# Display result
print("Updated Array:")
print(arr)
```
## Output
<img width="753" height="488" alt="WhatsApp Image 2026-06-02 at 9 17 17 AM" src="https://github.com/user-attachments/assets/65ccd07d-a710-428c-be36-bf4c9d6d8712" />

## Result
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position is successfully.
