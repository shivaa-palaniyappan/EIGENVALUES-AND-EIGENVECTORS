# EXP-4 EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the built-in functions for calculations
### Step 2: 
Prepare the lists from the each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SHIVAA PALANIYAPPAN V
#RegisterNumber:212223110050
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigvalues,eigvectors= np.linalg.eig(matrix)
print("Eigen values are",eigvalues,"and Eigen Vectors are",eigvectors)
```
## Output:
![image](https://github.com/shivaa-palaniyappan/EIGENVALUES-AND-EIGENVECTORS/assets/146915611/72608d37-74d5-45bd-90bd-12ca29bc9748)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
