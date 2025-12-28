# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd
dict=eval(input())
df = pd.DataFrame(dict)
print('Original Dataframe','\n',df)

new_row=eval(input())
df2=pd.DataFrame([new_row],
columns=df.columns)
combined=pd.concat([df,df2],ignore_index=True)
print('combined Dataframe','\n',combined)
```


## Output
<img width="237" height="662" alt="image" src="https://github.com/user-attachments/assets/6a77207a-77b7-4f30-9432-eab8508ff951" />

## Result
Executed successfully.
