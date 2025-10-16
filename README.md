# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start and import the library
### Step 2: Create a 2D NumPy array a with given elements
### Step 3: Use the function np.linalg.eig(a) to find the eigenvalues and eigenvectors of the matrix a.
### Step 4: Print the eigenvalues and eigenvectors using the print() function.

## Program:
```
      developed by - POTHU SUMANTH
      reg no - 212224240115
```
      import numpy as np
      a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
      values,vectors = np.linalg.eig(a)
      print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```
## Output:

<img width="768" height="144" alt="Screenshot 2025-10-16 151655" src="https://github.com/user-attachments/assets/51ac928f-3789-4cc2-8ede-c04fcd0a308a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
