# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Write a python program to find eigen value.
### Step 2: Recieve an input.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Execute the code.


## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Vishnupriya
#RegisterNumber:22006962
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output: ![](eig.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
