# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy and scipy from python library 
2.Get input from user,using string concept  
3.Calculate lu product and decomposition of the given matrices 
4.Print the value of L
5.Print the value of U


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Gokul J 
RegisterNumber:22009062 
import numpy as np
from scipy.linalg import lu
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
Developed by:Gokul J
RegisterNumber:22009062 
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

*/
```

## Output:
(i)
  ![LU decompositon 1](https://user-images.githubusercontent.com/121165938/214523464-dfc08bc3-fd30-4627-87b5-c7297a71a90a.png)
  
(ii)

  ![LU decompositon 2](https://user-images.githubusercontent.com/121165938/214523565-d3d76f63-4d24-49cb-8427-dff7481ad21e.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

