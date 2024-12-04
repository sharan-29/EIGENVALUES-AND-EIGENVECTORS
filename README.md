# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Get the input matrix using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End The Program 

## Program:
```
Developed by:Sharan Kumar G 
RegisterNumber:24003909
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:
![image](https://github.com/user-attachments/assets/51909cc3-3010-4e31-9511-bfe8b754e6d7)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
