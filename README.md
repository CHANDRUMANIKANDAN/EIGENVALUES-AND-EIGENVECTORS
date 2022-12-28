# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare a list for each linear equation and assign in numpy.linalg()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalue and eigen vector using print() function. End the program


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: CHANDRU M
#RegisterNumber:22009010
import numpy as np
A = np.array([[2,2],[1,3]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:![Screenshot_20221228_070903](https://user-images.githubusercontent.com/118644502/209820867-91915ef6-781d-4349-bd7b-bd28ff0e5ebe.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
