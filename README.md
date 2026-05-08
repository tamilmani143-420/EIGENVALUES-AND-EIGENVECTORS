# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1: Import NumPy library for matrix operations.
### Step2: Define the matrix using np.array().
### Step3: Use np.linalg.eig() to compute both eigenvalues and eigenvectors of the matrix.
### Step4: Print the results to display eigenvalues and eigenvectors.

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: Thamizhmani M
#RegisterNumber: 212225040468
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigen_value,eigen_vector=np.linalg.eig(matrixA)
print("Eigen values are",eigen_value ,"and Eigen Vectors are",eigen_vector)
~~~
## Output:
<img width="1481" height="814" alt="Screenshot 2026-05-08 131214" src="https://github.com/user-attachments/assets/1d80ef49-0e2e-4269-b44c-ae51ea1005c7" />
<img width="1476" height="470" alt="Screenshot 2026-05-08 131527" src="https://github.com/user-attachments/assets/1ca797e1-70e5-4569-8583-a1f98efb0074" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
