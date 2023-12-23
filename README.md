# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Read the elements of augmented matrix into array a and b
2.Calculate elements of L and U 
3.Print L and U  
4.Find V by solving LV=B by forward substitution
5.Find X by solving UX=V by backward substitution
6.Print array X as the solution
## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by:Suriya prakash.S
RegisterNumber:23013599
'''
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
Developed by:Suriya prakash.S  
RegisterNumber: 23013599 
*/
```python
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A,B=eval(input()),eval(input())
lu,piv=lu_factor(A)
x = lu_solve((lu,piv),B)
print(x)
```
## Output:
(i) To find the L and U matrix
![image](https://github.com/arulsuriyalokeshy/LU-Decomposition/assets/149130151/b2591d40-d5b5-4827-a696-9372ebc5d19c)
(ii) To find the LU Decomposition of a matrix
![image](https://github.com/arulsuriyalokeshy/LU-Decomposition/assets/149130151/1f93e425-3860-40c7-bd45-a480b816e90d)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

