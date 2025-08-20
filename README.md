# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1 : Import the numpy module to use the built-in functions for calculation
### Step 2:  Prepare the lists from each linear equations and assign in np.array
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix
### Step 4: End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: S Sanjay
#RegisterNumber: 212224110047
import numpy as np

A = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]])


A_inv = np.linalg.inv(A)


np.set_printoptions(precision=8, suppress=True)
print(A_inv)

```

## Output:
<img width="703" height="267" alt="image" src="https://github.com/user-attachments/assets/804f21be-5d7b-461a-a001-c4ce0ee06db7" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

