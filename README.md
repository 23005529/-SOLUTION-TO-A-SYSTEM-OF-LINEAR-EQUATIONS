# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
NAME : ALIYA SHEEMA 

REFERENCE NUMBER : 23005529

DEPARTMENT : AIDS

## AIM :
To write a python program to find a solution to a system of linear equations.
## EQUIPMENT'S REQUIRED :
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM :
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
 Using the np.linalg.solve(), we can find the solutions.
### Step 4: End the program
## PROGRAM :
```
#Program to find the solution for the given linear equations.
#Developed by: ALIYA SHEEMA 
#RegisterNumber: 23005529

import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
solution=np.linalg.solve(A,B)
print(solution)
```
## OUTPUT :

Program to find the solution for the given linear equations.

![Alt text](output.png)

## RESULT : 
Thus the solutions for the linear equations are successfully solved using python program

