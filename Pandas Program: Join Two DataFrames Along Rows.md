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
student_data1 = {
    'name': ['Aryan', 'Maya', 'Karthik'],
    'score': [78, 82, 91]
}
df1 = pd.DataFrame(student_data1)

student_data2 = {
    'name': ['Sana', 'Rohan', 'Isha'],
    'score': [88, 95, 80]
}
df2 = pd.DataFrame(student_data2)
combined_df = pd.concat([df1, df2], axis=0)
print("Combined Student DataFrame (Row-wise Join):\n")
print(combined_df)

```
## Output
<img width="504" height="403" alt="Screenshot 2025-10-20 165936" src="https://github.com/user-attachments/assets/9e1c3c95-9fa9-433c-94a7-1bc8f0a83367" />
## Result
Thus, to write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is executed successfully.
