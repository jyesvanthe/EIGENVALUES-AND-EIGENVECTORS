# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
Define the matrix A
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the result in output screen using print()function

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: JYESVANTHE V
#RegisterNumber: 23013991
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vector=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vector)
```


## Output:
![Alt text](<Screenshot 2023-12-12 113129.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
