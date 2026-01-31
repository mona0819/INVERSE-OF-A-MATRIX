# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Load the numpy library to access optimized linear algebra subroutines.
### Step 2: Represent the system by defining a square matrix $A$ as a NumPy array object.
### Step 3: Use the np.linalg.inv() function. This function uses LU decomposition to solve for the inverse, provided the matrix is non-singular (its determinant is not zero).
### Step 4: Print the resulting inverse matrix to the terminal.

## Program:
```python
#Program to find the inverse of a matrix.
#Developed by: Mohana Priya D
#RegisterNumber: 212225230182
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
inverse=np.linalg.inv(a)
print(inverse)
```

## Output:
<img width="828" height="787" alt="image" src="https://github.com/user-attachments/assets/536e891f-5159-47ab-b340-98a2929a2d75" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

