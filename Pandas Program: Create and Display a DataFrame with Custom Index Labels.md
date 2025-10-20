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
exam_data = {
    'name': ['Aryan', 'Maya', 'Karthik', 'Sana', 'Rohan', 'Isha', 'Vikram', 'Tara'],
    'score': [88, 76, 92, 54, 61, 85, 79, 90],
    'attempts': [2, 1, 3, 2, 1, 3, 2, 1],
    'qualify': ['yes', 'yes', 'yes', 'no', 'no', 'yes', 'yes', 'yes']
}
labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h']
df = pd.DataFrame(exam_data, index=labels)
print("Exam Results DataFrame:\n")
print(df)
```
## Output
<img width="461" height="441" alt="Screenshot 2025-10-20 165428" src="https://github.com/user-attachments/assets/8d885db7-27f7-45ff-b455-24680f2371a1" />


## Result
Thus, to create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows is executed successfully.

