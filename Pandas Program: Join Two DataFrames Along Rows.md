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

````
import pandas as pd

student_data1 = {
    'Name': ['Anu', 'Ravi', 'Kiran'],
    'Score': [85, 92, 78]
}

student_data2 = {
    'Name': ['Meena', 'Karthik'],
    'Score': [88, 90]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

result = pd.concat([df1, df2], axis=0)
print(result)

````

## Output

<img width="627" height="340" alt="image" src="https://github.com/user-attachments/assets/e135e15f-6c33-46f9-8d0e-2006652bcade" />


## Result

Thus the program using Pandas to join two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame has been executed successfully.
