# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Rahul V
RegisterNumber: 212223240132


from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Rahul v
RegisterNumber: 212223240132
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![image](https://github.com/Rahulv2005/LU-Decomposition/assets/152600335/6bf7ecb2-cdd8-45dc-bc7c-69a04a4ee55a)
![image](https://github.com/Rahulv2005/LU-Decomposition/assets/152600335/17aa04b2-85b9-43f2-b335-b59126d58787)
![image](https://github.com/Rahulv2005/LU-Decomposition/assets/152600335/f32effcc-e3c3-4f6c-9a9b-3999cddd3eff)
![image](https://github.com/Rahulv2005/LU-Decomposition/assets/152600335/97b48517-a65e-469e-abd7-10a2a1a7b590)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

