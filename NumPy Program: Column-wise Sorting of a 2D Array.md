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

````

rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

elements = []
print("Enter the elements row-wise:")

for _ in range(rows):
    row = list(map(int, input().split()))
    elements.append(row)

array = np.array(elements)
sorted_array = np.sort(array, axis=0)

print("Original Array:")
print(array)
print("Column-wise Sorted Array:")
print(sorted_array)
````

## Output

<img width="636" height="551" alt="image" src="https://github.com/user-attachments/assets/d528d349-0ed1-479d-8a19-d8d1b9b7c581" />


## Result

Thus the program that sorts the elements in each column of a given 2D array in ascending order has been executed successfully.
