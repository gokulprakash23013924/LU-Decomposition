# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. start the progran
2. get an input from the user
3. display the value og L and U
4. end the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: GOKUL PRAKASH M
RegisterNumber: 23013924
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: GOKUL PRAKASH M
RegisterNumber: 23013924
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
![image](https://github.com/gokulprakash23013924/LU-Decomposition/assets/150231472/3193e8ab-1785-47be-a376-76c10fa0756f)
![image](https://github.com/gokulprakash23013924/LU-Decomposition/assets/150231472/561149aa-aa31-44a3-a0b2-ce7981cdc5c5)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

