# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 : Import the numpy module to use the builtin function for calculation.
Step 2: Prepare the list from linear equation and assign in np.array().
Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Step 4: End of the program.

## Program:
```python
#Program to find the rank of a matrix.
#Developed by: MARELA DHARANESH
#RegisterNumber: 22000785
import numpy as np
a=np.array([[1,2,3],[3,6,9]])
b=np.linalg.matrix_rank(a)
print(b)
```

## Output:
![Screenshot (13)](https://user-images.githubusercontent.com/118707669/211201028-3d69a7e2-ccae-4be1-9dec-4322752299f8.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
