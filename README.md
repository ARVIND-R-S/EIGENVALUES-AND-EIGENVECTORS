# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import os and numpy
### Step 2: creating array "a" which has the matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: printing the eigen values and eigen vectors of the respective matrix

## Program:
### #Program to find the eigen values and eigen vectors.
### #Developed by: Arvind R S
### #RegisterNumber: 26017022
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
### b,c=np.linalg.eig(a)
### print(f"Eigen values are {b} and Eigen Vectors are {c}")
## Output:
<img width="1330" height="837" alt="image" src="https://github.com/user-attachments/assets/89dacddf-8c12-4ddc-b462-88ad4a2c73f8" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
