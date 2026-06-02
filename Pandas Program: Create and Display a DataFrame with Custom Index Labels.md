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
import numpy as np

# Create dictionary
exam_data = {
    'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily'],
    'score': [12.5, 9, 16.5, np.nan, 9],
    'attempts': [1, 3, 2, 3, 2],
    'qualify': ['yes', 'no', 'yes', 'no', 'no']
}

# Index labels
labels = ['a', 'b', 'c', 'd', 'e']

# Create DataFrame
df = pd.DataFrame(exam_data, index=labels)

# Display DataFrame
print(df)
```

## Output
<img width="844" height="295" alt="WhatsApp Image 2026-06-02 at 9 17 28 AM" src="https://github.com/user-attachments/assets/830814de-dcd5-409c-bd8a-8e77768924db" />

## Result
To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows is successfully.
