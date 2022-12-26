# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
inport equal to numpy as np
### Step 2: 
consider a as a variable and give the values in the list
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
print the result of  the rank matrix
## Program:
```
#Program to find the rank of a matrix.
#Developed by: 
#RegisterNumber:
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![output](rank.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

