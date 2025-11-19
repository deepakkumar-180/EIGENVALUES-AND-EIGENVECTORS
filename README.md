# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:s.deepakkumar
#RegisterNumber:25016457
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
b=np.array(a)
values,vectors=np.linalg.eig(b)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1920" height="1080" alt="Screenshot 2025-11-19 113755" src="https://github.com/user-attachments/assets/ed78ea15-7c47-4cd5-9065-813dfb79fc22" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
