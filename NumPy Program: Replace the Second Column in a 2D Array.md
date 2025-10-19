# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
import numpy as np
# Example input: [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
arr = np.array(eval(input("Enter a 2D NumPy array: ")))
new_col = np.array(eval(input("Enter the new column: ")))
arr = np.delete(arr, 1, axis=1)
arr = np.insert(arr, 1, new_col, axis=1)
print("Updated array:")
print(arr)


## Output
<img width="815" height="707" alt="image" src="https://github.com/user-attachments/assets/67640e9e-3dc4-4849-9f43-cdb6a9aec92f" />


## Result
A **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position is excuted sucessful.

