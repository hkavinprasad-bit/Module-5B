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

# Create first DataFrame
student_data1 = {
    'Name': ['John', 'Alice', 'Bob'],
    'Marks': [85, 90, 78]
}

df1 = pd.DataFrame(student_data1)

# Create second DataFrame
student_data2 = {
    'Name': ['David', 'Emma', 'Sophia'],
    'Marks': [88, 92, 81]
}

df2 = pd.DataFrame(student_data2)

# Concatenate DataFrames row-wise
combined_df = pd.concat([df1, df2], axis=0)

# Display Result
print(combined_df)
```

## Output
<img width="750" height="432" alt="WhatsApp Image 2026-06-02 at 9 17 39 AM" src="https://github.com/user-attachments/assets/c6a1165b-769f-4afd-87ba-eb98d5fe02b0" />

## Result
To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is successfully.
