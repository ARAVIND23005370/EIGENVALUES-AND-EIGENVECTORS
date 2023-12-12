# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in function for calculation.
### Step 2: prepare the listfrom each linear equation and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
~~~python
#Program to find the eigen values and eigen vectors.
#Developed by: ARAVIND R
#RegisterNumber:23005370
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vector=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vector))
~~~
## Output:
![image](https://github.com/ARAVIND23005370/EIGENVALUES-AND-EIGENVECTORS/assets/148514836/3b317eab-1144-4983-b5a3-25a4f12546c3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
