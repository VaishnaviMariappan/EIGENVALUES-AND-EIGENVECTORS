# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : 
Import numpy as np 

### Step 2: 
Assign in np.array() in eigen values and eigen vector

### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
Print the eigen values and vectors and end the program


## Program:
```
#Program to find the Eigenvalues and Eigen Vectors
#Developed by:Vaishnavi M
#RegisterNumber:21500310
import numpy as np
A=np.array([[4,2],[2,4]])
values,vector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![output](./output.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
