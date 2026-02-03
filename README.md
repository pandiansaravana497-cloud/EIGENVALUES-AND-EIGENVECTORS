# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import NumPy library, np.linalg is its linear algebra module, which provides the eig() function to compute eigenvalues and eigenvectors.
### Step 2: 
Create a square matrix, Eigenvalues and eigenvectors can only be found for square matrices (same number of rows and columns).
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the result, This line displays the eigenvalues and eigenvectors.
## Program:
```Python
#Program to find the eigen values and eigen vectors.
#Developed by:PON SARAVANA PANDIAN B
#RegisterNumber:212225230207
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1241" height="779" alt="Screenshot 2026-02-03 183709" src="https://github.com/user-attachments/assets/2db01826-6293-4e6e-a2fa-d52f686f3237" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
