# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import NumPy and SciPy
2.Accept input for the matrix 'A'
3.Perform LU decomposition
4.Print the lower and upper triangular matrices

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: karthi keyan k
RegisterNumber: 23013936
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```


'''Program to solve a matrix using LU decomposition.
Developed by: karthi keyan
RegisterNumber: 23013936
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![Screenshot 2023-12-21 201429](https://github.com/Karthi051/LU-Decomposition/assets/148327224/81b5752c-3a4d-4273-9c9f-d61cf21629ab)
![Screenshot 2023-12-21 201611](https://github.com/Karthi051/LU-Decomposition/assets/148327224/daacc893-c8fe-4d89-8ded-0901997ebefb)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

