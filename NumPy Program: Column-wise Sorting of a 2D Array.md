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
arr = np.array([
    [4, 5, 6],
    [1, 2, 3],
    [7, 8, 9]
])
sorted_arr = np.sort(arr, axis=0)
print("Original Array:")
print(arr)
print("\nColumn-wise Sorted Array:")
print(sorted_arr)
```

## Output
<img width="385" height="390" alt="Screenshot 2025-10-20 163839" src="https://github.com/user-attachments/assets/442c5c1a-5bb3-4274-98dc-5e4f389aa495" />

## Result
Thus, to write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is executed successfully.
