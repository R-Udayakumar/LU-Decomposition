# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Import numpy library as np

2. Create a matrix using np.array() 

3. Using scipy.linalg.lu() find L and U.

4. Also use scipy.linalg.lu_solve() to get the result for LU Decomposition 

5. Get the output and end the program


## Program:
(i) To find the L and U matrix
```python
Program to find the L and U matrix.
Developed by: Udayakumar R
RegisterNumber: 22008609

import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)

```
(ii) To find the LU Decomposition of a matrix
```python
Program to find the LU Decomposition of a matrix.
Developed by: Udayakumar R
RegisterNumber: 22008609

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

```

## Output:
(i).

![OUTPUT1](output2%20(2).png)

(ii).

![OUTPUT2](output2%20(1).png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

