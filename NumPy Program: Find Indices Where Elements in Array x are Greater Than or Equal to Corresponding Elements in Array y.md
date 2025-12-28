# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np
import ast

# Read input and convert to Python list
arr_input = input().strip()
arr_list = ast.literal_eval(arr_input)

# Convert to numpy array
A = np.array(arr_list)

# Compute and print standard deviation
print(np.std(A))
```

## Output
<img width="733" height="212" alt="image" src="https://github.com/user-attachments/assets/7c1b92f6-d2e2-41f3-a697-35624a46575d" />

## Result
Executed successfully.
