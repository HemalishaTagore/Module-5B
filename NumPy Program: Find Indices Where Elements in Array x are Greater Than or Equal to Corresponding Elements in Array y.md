# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np
x = np.array([9,7,6,8,10])
y = np.array([5,1,11,4,3])
condition = x >= y
indices = np.where(condition)
print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices[0])
```
## Output
<img width="412" height="229" alt="Screenshot 2025-10-20 164400" src="https://github.com/user-attachments/assets/e3b748f6-d50e-4d1f-89b9-bf0c617a2bff" />

## Result
Thus, to write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y` is executed successfully.
