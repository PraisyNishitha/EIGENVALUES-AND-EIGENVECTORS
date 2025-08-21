# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Import the NumPy library using import numpy as np.
Step 2:
Define the square matrix A using np.array().
Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalues and second is eigenvectors) of the given matrix.
Step 4:
Print the eigenvalues and eigenvectors. 

## Program:
~~~
import numpy as np

A = np.array([
    [-2,  2, -3],
    [ 2,  1, -6],
    [-1, -2,  0]
])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
~~~
## Output:
<img width="1506" height="697" alt="ex4" src="https://github.com/user-attachments/assets/d0c283d1-ed85-4541-a53f-8bc776875053" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
