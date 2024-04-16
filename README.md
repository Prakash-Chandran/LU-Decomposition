# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable 'X'.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: PRAKASH C
RegisterNumber: 212223240122
*/
```
````
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
````
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: PRAKASH C
RegisterNumber: 212223240122
*/
```
````
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv),B)
print(x)
````
## Output:

![Screenshot 2024-04-16 210015](https://github.com/Prakash-Chandran/LU-Decomposition/assets/147120899/367b2162-12de-4f02-abdd-4a3ac300bd5c)

![Screenshot 2024-04-16 210028](https://github.com/Prakash-Chandran/LU-Decomposition/assets/147120899/72d2a2b4-8668-4fa4-ab1f-616886ce053b)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

