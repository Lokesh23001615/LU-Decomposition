# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start a programme.
2. import scipy.linalg and numpy
3. get input from the user and store in array and print L
4. using L find U of the matrix and later find LU of the matrix
5. End the programme.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: M.Lokesh
RegisterNumber: 23001615
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: M.Lokesh
RegisterNumber: 23001615

# To print X matrix (solution to the equations)
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
![lu decomposition]()
![](image.png)
![Alt text](image-1.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

