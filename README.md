# Date: 06/04/2024
# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation.
### Step 2:
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
```
Developed by: Supraja B
Register number: 2305002026

import numpy as np
A =np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are{} and Eigen vectors are {}".format(values,vectors))
```
## Output:![image](https://github.com/Supraja0510/EIGENVALUES-AND-EIGENVECTORS/assets/155217478/5ab2c87e-9f6a-4866-90c9-9b4eabf61963)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
