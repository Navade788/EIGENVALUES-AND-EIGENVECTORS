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
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```python
import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors= np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/user-attachments/assets/00f0c540-e73a-4b5e-bb85-e4d5bcd14a6a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
