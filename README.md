# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
import numpy as np
from  scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![lu decomposition]()
![Screenshot 2024-11-27 220928](https://github.com/user-attachments/assets/332c7a06-a418-4060-9630-8987207d9f7c)

![Screenshot 2024-11-27 220941](https://github.com/user-attachments/assets/377a34b6-1e80-449d-a844-a8328f2cab0b)






## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

