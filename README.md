# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Balaji SK
#RegisterNumber: 2305003001
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/adhi2k/EIGENVALUES-AND-EIGENVECTORS/assets/145216997/53839137-cc25-4b64-b2fa-1eb827e80cf7)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
