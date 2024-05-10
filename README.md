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
#Developed by : VASANTH KUMAR V
#Register Number : 2305002027

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
#Developed by : MADHUMITHA V
#Register Number : 2305002013

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A= np.array(eval(input()))
B= np.array(eval(input()))
lu, ply = lu_factor(A)
x= lu_solve((lu,ply),B)
print(x)
```
## Output:
![WhatsApp Image 2024-05-10 at 11 54 24_4b97b442](https://github.com/vasanth0228/LU-Decomposition/assets/155505264/54eac392-8e15-4056-ba31-c0486541e62d)
![WhatsApp Image 2024-05-10 at 11 54 24_7fde761d](https://github.com/vasanth0228/LU-Decomposition/assets/155505264/44741ea0-1241-40b9-b5cb-5f0bc0bd808e)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.


