# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using np.linalg.inv(),we can find the inverse of a matrix

Step 4:
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: S.PAVAN
#RegisterNumber: 212225040296

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
soln=np.linalg.inv(A)
print(soln)
```
## Output:
<img width="1896" height="971" alt="image" src="https://github.com/user-attachments/assets/803d17d0-f731-4db9-85fd-b3f96df8da8d" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

