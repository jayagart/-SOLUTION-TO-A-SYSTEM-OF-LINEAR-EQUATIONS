# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
import numpy as np
A=[[1,-3], [3,1]]
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)
```
## Output:
![image](https://github.com/user-attachments/assets/1a1b898b-70c4-4739-9917-5e34de9e3b4a)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

