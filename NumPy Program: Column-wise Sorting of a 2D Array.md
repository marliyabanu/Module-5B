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
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

print("Enter the elements row-wise:")
elements = []
for i in range(rows):
    row = list(map(int, input(f"Row {i+1}: ").split()))
    elements.append(row)
original_array = np.array(elements)
sorted_array = np.sort(original_array, axis=0)
print("\nOriginal Array:")
print(original_array)

print("\nColumn-wise Sorted Array:")
print(sorted_array)


## Output
<img width="822" height="722" alt="image" src="https://github.com/user-attachments/assets/908931f8-848f-4957-9b85-f3d9dc421633" />


## Result
A **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is excuted sucessful .
