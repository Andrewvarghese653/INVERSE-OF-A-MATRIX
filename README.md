# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: 
End the program

## Program:
```python
import numpy as np
A = np.array([[2,1,1],[1,1,1],[1,-1,2]])
B = np.linalg.inv(A)
print(B)
```
## Output:
<img width="1134" alt="Screenshot 2023-11-16 at 10 25 16 PM" src="https://github.com/Andrewvarghese653/INVERSE-OF-A-MATRIX/assets/145822115/c5bed2d3-a2a1-4653-9d86-d368e5547294">

## Result:
Thus the inverse of given matrix is successfully solved using python program

