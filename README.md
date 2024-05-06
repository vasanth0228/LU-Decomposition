## LU Decomposition
## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
Hardware – PCs

Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm :
1.Read the elements of augmented matrix into arrays a and b

2.Calculate elements of L and U

3.Print elements of L and U

4.Find V by solving LV = B by forward substitution

5.Find X by solving UX = V by backward substitution

6.Print Array X as the solution
## Program:
(i) To find the L and U matrix
```
#Developed by : CHITHRADHEEP R
#Register Number : 2305002003

import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
```
#Developed by : CHITHRADHEEP R
#Register Number : 2305002003

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A= np.array(eval(input()))
B= np.array(eval(input()))
lu, ply = lu_factor(A)
x= lu_solve((lu,ply),B)
print(x)
```
## Output:
![Screenshot 2024-05-06 093744](https://github.com/Chithradheep/LU-Decomposition/assets/155504933/55ffa5a0-2433-418f-9040-b0e83dc489d0)
![Screenshot 2024-05-06 093811](https://github.com/Chithradheep/LU-Decomposition/assets/155504933/a539a0a1-5820-47f1-9347-c30baf8676b4)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.


