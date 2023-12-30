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
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
lin=np.linalg.solve(A,B)
print(lin)
## Output:
![WhatsApp Image 2023-12-31 at 01 27 34_26d2b53c](https://github.com/ibrahimfedahs/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150319493/1519155d-369f-44ad-bf1a-a5f3eb1cf052)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

