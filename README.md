# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Take the given square matrix A.
2.Assume 𝐴=𝐿𝑈, where 𝐿 is lower triangular and 𝑈 is upper triangular.
3.Initialize L as an identity matrix.
4.Compute elements of U row by row using values of A and previously found elements.
5.Compute elements of L column by column using values of A and U.
6.Repeat the process until all elements of L and U are obtained.
7.The matrices L and U are the required decomposition.

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

