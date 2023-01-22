# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1:
Import the numpy module to use the built-in functions for calculation

### Step 2: 
Prepare the lists from each linear equations and assign in np.array()

### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4: 
End the program

## Program:
```
#Program to find the rank of a matrix.
#Developed by: sakthivel R
#RegisterNumber:22009121
import numpy as np
A=np.array([[1,2,3],[3,6,9]])
rank=np.linalg.matrix_rank(A)
print(rank)


```

## Output:

![Screenshot from 2022-12-28 09-38-10](https://user-images.githubusercontent.com/120550359/209755904-5952b2e7-1750-4603-a528-02eb0a82c945.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

