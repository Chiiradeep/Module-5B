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
~~~
import numpy as np
x=np.array(eval(input()))
sorted=np.sort(x,axis=1)
print("Given array ")
print("",x,"\n")
print(sorted)
~~~

## Output
![439322848-fe2b0019-a533-4b1d-8e6b-1465ca52b498](https://github.com/user-attachments/assets/f5033a09-9c30-46be-a8a8-6cfcf59e620a)


## Result
Thus,the program has been executed successfully.

----

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
~~~
import numpy as np
x=np.array(eval(input()))
y=np.array(eval(input()))
great=np.where(x>y)
equal=np.where(x==y)
print(great)
print(equal)
~~~

## Output
![439325031-4c26dcc1-9990-4dd1-866f-dc1c6f347217](https://github.com/user-attachments/assets/cd7eb8f1-5360-4de2-b241-ffd500043e09)


## Result
Thus,the program has been executed successfully.

----


