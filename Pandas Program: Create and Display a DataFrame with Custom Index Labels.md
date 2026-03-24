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

import pandas as pd

# Given dictionary
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [23, 25, 22],
    'City': ['NY', 'LA', 'Chicago']
}

# Create DataFrame with custom index
df = pd.DataFrame(data, index=['A', 'B', 'C'])

# Display DataFrame
print(df)

## Output
<img width="1919" height="963" alt="image" src="https://github.com/user-attachments/assets/01da0736-1b44-4f14-b8e2-40771199cd00" />

## Result
