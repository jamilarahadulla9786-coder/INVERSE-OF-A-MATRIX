# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program.
### Step 2: Import the required libraries:
### Step 3: Set the OpenBLAS thread count:
### Step 4: Create the matrix:

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="1030" height="669" alt="{CB14952F-3FCB-42F6-B245-87647714A3EA}" src="https://github.com/user-attachments/assets/3699ef6f-4230-453d-9e07-d4e2658126f5" />

## Result:
Thus the inverse of given matrix is successfully solved using python program


