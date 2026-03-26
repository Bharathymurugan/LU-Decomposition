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
'''Program to find L and U matrix using LU decomposition.
Developed by: Bharathy M
RegisterNumber: 212225040046/ 25013139
'''
import numpy as np
from scipy.linalg import lu
matrix = np.array(eval(input()))
P, L, U = lu(matrix)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Bharathy M
RegisterNumber: 212225040046/25013139
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
*/
```

## Output:
TO FIND L AND U MATRIX
![alt text](<Screenshot 2026-03-25 192142.png>)
![alt text](<Screenshot 2026-03-26 103251.png>)
 
TO FIND LU DECOMPOSITION OF A MATRIX
![alt text](<Screenshot 2026-03-25 192218.png>)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

