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

import numpy as np

# Create 2D array
arr = np.array([[9, 3, 5],
                [2, 8, 1],
                [7, 4, 6]])

# Sort column-wise (axis=0)
sorted_arr = np.sort(arr, axis=0)

print("Original array:\n", arr)
print("Column-wise sorted array:\n", sorted_arr)

## Output
<img width="1919" height="961" alt="image" src="https://github.com/user-attachments/assets/c2f335ac-cbad-43ad-922e-5d06ce73a122" />

## Result
