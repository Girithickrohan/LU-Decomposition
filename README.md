# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Get the dimensions of the matrix
2. Initialize matrices L and U
3.  Perform LU decomposition
4.  Return the decomposed matrices L and U

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Girithick Rohan 
RegisterNumber: 23003797
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Girithick Rohan
RegisterNumber: 23003797
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
Output 1:

![image](

Output 2:

![image](


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

