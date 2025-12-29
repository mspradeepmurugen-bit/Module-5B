# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
arr=np.array([[2, 3, 4],
              [9, 6, 4],
              [12, 8, 5]])
sort_arr=np.sort(arr, axis=0)
print(f"Original array:\n",arr)
print(f"sorted array:\n",sort_arr)
```

## Output
<img width="946" height="286" alt="Screenshot 2025-12-29 203000" src="https://github.com/user-attachments/assets/daac4a95-f430-4e3f-95ac-6b23942ae599" />

## Result
thus the python program is executed sucessfully!
