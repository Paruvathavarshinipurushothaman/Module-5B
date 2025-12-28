# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd
a=eval(input())
b=eval(input())
c=eval(input())
d=pd.DataFrame({'Name':a, 'Age':b,'Designation':c})
print(d)
e=d.sort_values(by='Age')
print(e)
```

## Output
<img width="1006" height="323" alt="image" src="https://github.com/user-attachments/assets/7306ddd3-2451-46a0-b887-0defba9f2c40" />

## Result
Executed successfully.
