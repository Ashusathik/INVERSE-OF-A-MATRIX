# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation
### Step 2: 
Prepare the lists for the given matrix and assign in np.array()
### Step 3: 
Using the np.linalg.inv()we can find the inverse of the given matrix
### Step 4: 
end of the program

## Program:

# Developed by: ASHRATHI S
# RegisterNumber:24900260
    import numpy as np
        A = np.array([
            [2, 1, 1],
            [1, 1, 1],
            [1, -1, 2]
        ])
        soln=np.linalg.inv(A)
        print(soln)
## Output:
![alt text](<Screenshot 2024-12-23 193338.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

