# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

##Step 1:Import the numpy module to use the built-in functions for calculation
##Step 2:Prepare the lists from each linear equations and assign in np.array()
##Step 3:Using the np.linalg.solve(), we can find the solutions.
##Step 4:End the program

## Program:
#Program to find the rank of a matrix.
#Developed by: Bavin Balaji R 
#RegisterNumber:212225040045
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,2,3],[3,6,9]])
rank = np.linalg.matrix_rank(A)
print(rank)

## Output:
<img width="1479" height="828" alt="image" src="https://github.com/user-attachments/assets/38a477ec-877a-41ea-9049-41087fbb8a27" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

