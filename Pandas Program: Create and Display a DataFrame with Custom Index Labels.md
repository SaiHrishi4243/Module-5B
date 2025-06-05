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

```python

import pandas as pd
import numpy as np

exam_data = {
    'name': ['Anastasia', 'Dima', 'Katherine', 'James'],
    'score': [12.5, 9.0, 16.5, np.nan],
    'attempts': [1, 3, 2, 3],
    'qualify': ['yes', 'no', 'yes', 'no']
}

labels = ['a', 'b', 'c', 'd']

df = pd.DataFrame(exam_data, index=labels)
print(df)

```

## Output

![image](https://github.com/user-attachments/assets/ebc1ae16-f9a5-40c9-88a0-b4be6f134113)

## Result

Thus implemented the python program to create and display a DataFrame using the Pandas library in Python from a given dictionary, and apply specific index labels to the rows.
