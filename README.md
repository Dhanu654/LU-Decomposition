# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by:  DHANUSYA K
RegisterNumber:  23006651
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by:  DHANUSYA K
RegisterNumber: 23006651
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution) 
*/
```

## Output:
![lu decomposition]()
![Screenshot 2023-12-20 214814](https://github.com/Dhanu654/LU-Decomposition/assets/148514965/0958f2b9-7dcd-41bb-b968-416c80a4d6a3)
![Screenshot 2023-12-20 214840](https://github.com/Dhanu654/LU-Decomposition/assets/148514965/581cb09e-d8f3-41f4-a2b1-fdd0147810f1)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

