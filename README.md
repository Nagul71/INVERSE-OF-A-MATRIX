# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
We have created a matrix using array and we will find inverse of this.
### Step 3: 
We can find the inverse of the martix by using np.linalg.inv and passing the matrix.
### Step 4: 
Finally, print the value of the inverse of the matrix.
## Program:
```#Program to find the inverse of a matrix.
#Developed by: K.Nagul
#RegisterNumber: 22008933
import numpy as np
A = np.array([[2,1,1],[1,1,1],[1,-1,2]])
result = np.linalg.inv(A)
print(result)
```
## Output:
![output](/Screenshot%20from%202022-12-24%2021-11-56.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

