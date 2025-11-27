# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : find the given matrix A
### Step 2: find the determinant of the matrix A to check weather the inverse  exist
### Step 3: compute the adjoint of the matrix A(or apply Gauss-jordan method)
### Step 4: find the inverse of A

## Program:
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
inverse_A=np.linalg.inv(A)
print(inverse_A)
## Output:
<img width="1894" height="913" alt="Screenshot 2025-11-27 111832" src="https://github.com/user-attachments/assets/422a6f87-baf2-43e7-9301-b526723c5867" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

