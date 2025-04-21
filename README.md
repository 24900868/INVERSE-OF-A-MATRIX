# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step 1: Import the numpy module to use the built-in functions for calculation
Step 2: Prepare the lists from each linear equations and assign in np.array()
Step 3: Using the np.linalg.inverse(), we can find the solutions.
Step 4: End the program
```
## Program:
```
#Developed by: M.Mahalakshmi
#RegisterNumber: 212224230148
```
```
import numpy as np
matrix = np.array([[2, 1, 1],
                   [1, 1, 1],
                   [1, -1, 2]])
det = np.linalg.det(matrix)
if det == 0:
    print("The matrix is not invertible (its determinant is zero).")
else:
    inverse_matrix = np.linalg.inv(matrix)
    print(inverse_matrix)
```

## Output:

![Screenshot 2025-03-03 084355](https://github.com/user-attachments/assets/efeaf3b2-addc-4c7e-be26-3231034cf188)


## Result:
Thus the inverse of given matrix is successfully solved using python program

