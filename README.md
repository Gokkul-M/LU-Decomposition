# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### step 1:
Import numpy library using import statement
### step 2:
From scipy package import lu()
### step 3:
Get input from user and pass it as an array 
### step 4:
Get P,LU matrix using lu()
### step 5:
Print L and U matrix
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:Gokkul M
RegisterNumber:212223240039 
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
'''Program to solve a matrix using LU decomposition.
Developed by:Gokkul M
RegisterNumber: 212223240039
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/Gokkul-M/LU-Decomposition/assets/144870543/18065521-35a6-4da3-a641-549675ff0675)
![image](https://github.com/Gokkul-M/LU-Decomposition/assets/144870543/30d323ad-2d9d-43a2-af97-2c5c564b855c)
(ii) To find the LU Decomposition of a matrix
![image](https://github.com/Gokkul-M/LU-Decomposition/assets/144870543/e276eb16-7f28-4ca4-9f2b-077e0a94ba5f)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

