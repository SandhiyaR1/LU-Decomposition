# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. import numpy moduleto use the built-in functions for calculation.
2. from scipy.linalg import lu.
3. get input from the user
4. assign the value to P,L and U
5. end the program

## Algorithm

1.import numpy as np

2.import lu_factor and lu_solve from scipy.linalg

3.get the users input

4.apply in the formula

5.print the decomposed matrix

6.end the program.

## Program:
(i) To find the L and U matrix
``` python
#Program to find the L and U matrix.
#Developed by: sandhiya
#RegisterNumber: 22001197


import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
#Program to find the LU Decomposition of a matrix.
#Developed by: sandhiya.R
#RegisterNumber: 22001197

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
To find the L and U matrix
![output](/ludecomposition1.png)
Program to find the LU Decomposition of a matrix.
![output](/ludecomposition2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

