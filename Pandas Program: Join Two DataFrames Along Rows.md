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
~~~c
import pandas as pd
data1 = {
    'Name': ['Alice', 'Bob'],
    'Age': [24, 27],
    'City': ['New York', 'Los Angeles']
}
data2 = {
    'Name': ['Charlie', 'David'],
    'Age': [22, 29],
    'City': ['Chicago', 'San Francisco']
}

df1 = pd.DataFrame(data1)
df2 = pd.DataFrame(data2)
result_df = pd.concat([df1, df2], axis=0, ignore_index=True)
print("Concatenated DataFrame:")
print(result_df)
~~~
## Output
![Screenshot 2025-05-11 130728](https://github.com/user-attachments/assets/f4ddbe3c-7a44-47c9-b291-a96acf695bf0)


## Result
Thus the program has been executed successfully.
