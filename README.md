# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

### Step 1: Import required libraries numpy and scipy.linalg.

### Step 2: Input the matrix/matrices using eval(input()).

### Step 3: Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().

### Step 4: Print the results L and U matrices or solution X matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NETHRA .K
RegisterNumber: 212224230184


import numpy as np
from scipy.linalg import lu

a=np.array(eval(input()))
p,l,u=lu(a)

print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: NETHRA.K
RegisterNumber: 212224230184


'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve

a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```

## Output:
![lu decomposition]()

<img width="1449" height="998" alt="Screenshot 2025-08-28 094042" src="https://github.com/user-attachments/assets/f4142f60-1606-4e18-b150-f6d6df7a312d" />
<img width="1740" height="1010" alt="Screenshot 2025-08-28 094154" src="https://github.com/user-attachments/assets/c5203bac-aa62-4228-9b69-d917ad19528f" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

