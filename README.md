# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM:
## Algorithm for L and U Matrix
1. Import numpy as np.
2. from scipy.linalg import lu.
3. Enter the lists from each linear equations and assign in np.array().
4. Using lu(), store it in three variables.
5. Print the L and U Matrix.
6. End the program.

## Algorithm for LU Decomposition
1. Import numpy as np.
2. from scipy.linalg import lu_factor,lu_solve.
3. Enter the lists from each linear equations and assign in np.array().
4. Enter the lists from each linear equations and assign in np.array().
5. Using lu_factor(), store it in two variables.
6. Using lu_solve(), we can find L and U matrix.
7. Print the result.
8. End of the program.


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Hari Prasath. P
RegisterNumber: 23005079
'''
import numpy as np
from scipy.linalg import lu
b=np.array(eval(input()))
P,L,U=lu(b)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![output](/Screenshot%202023-07-29%20124315.png)
![output](/Screenshot%202023-07-29%20124408.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

