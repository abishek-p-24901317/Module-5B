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
Developed by: Abishek P
Register Number: 212224240002
import numpy as np
arr=np.array(eval(input()))
print("Given array")
print(arr)
print()
print(np.sort(arr,axis=0))
```
## Output
![443940483-63dfd086-76fc-4664-af62-98938985f081](https://github.com/user-attachments/assets/1c8faa08-c244-4ad5-bed9-4552ca9f484e)

## Result
Thus the program that sorts the elements in each column of a given 2D array in ascending order is executed successfully
