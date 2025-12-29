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
student_data1={
    'name':['arun', 'Bala'],
    'score':[85, 75],
}
df1=pd.DataFrame(student_data1)
student_data2={
    'name':['chitra', 'Deepak'],
    'score':[35, 67],
}
df2=pd.DataFrame(student_data2)
combined_data=pd.concat([df1, df2],axis=0)
print(combined_data)
```

## Output
<img width="1021" height="348" alt="Screenshot 2025-12-29 204822" src="https://github.com/user-attachments/assets/1c901c19-ce45-4b73-a656-259ff1baf667" />

## Result
thus the python program is executed sucessfully
