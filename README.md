# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy module to use the built-in functions for calculation
2. prepare the lists from each linear equation and assign in np.array()
3. using the np.lin.alg.solve(),we can find the solutions
4. end the program

## Program:
(i) To find the L and U matrix

'''
Program to find L and U matrix using LU decomposition.
Developed by: akash m
RegisterNumber: 212223240003

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
Program to solve a matrix using LU decomposition.
Developed by: akash m
RegisterNumber: 212223240003

from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:

![image](https://github.com/akashmano/LU-Decomposition/assets/137408306/ba0ba079-2c7f-427d-b273-31967c9d2151)


![image](https://github.com/akashmano/LU-Decomposition/assets/137408306/b62f62a3-c2e8-4d27-9169-b175286aaad5)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

