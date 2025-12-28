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

# Given 2D array
arr = np.array([[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]])

# Delete the second column (index 1)
arr_deleted = np.delete(arr, 1, axis=1)

# New column to insert
new_column = np.array([[10],
                       [11],
                       [12]])

# Insert the new column at index 1
arr_updated = np.insert(arr_deleted, 1, new_column, axis=1)

print("Updated Array:")
print(arr_updated)
```

## Output
<img width="233" height="150" alt="image" src="https://github.com/user-attachments/assets/c23955a7-2292-44f9-bcc8-7ff88d9114bc" />

## Result
Executed successfully.
