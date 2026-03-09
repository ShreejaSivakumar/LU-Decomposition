# LU Decomposition 

# NAME: SHREEJA R S
# REF.NO : 25017561

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Start the program.

2. Import the NumPy library and the lu function from scipy.linalg to perform LU decomposition.

3. Input the matrix that you want to decompose.

4. Apply LU decomposition using lu(A) to obtain matrices 𝑃, 𝐿, and 𝑈.
   - 𝑃 is the permutation matrix.
   - 𝐿 is the lower triangular matrix.
   - 𝑈 is the upper triangular matrix.

5. Display the 𝐿 and 𝑈 matrices as output.

6. End the program.


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SHREEJA R S 
RegisterNumber: 25017561
*/


import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SHREEJA R S 
RegisterNumber: 25017561
*/


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```

## Output:

 
![Screenshot_9-3-2026_19036_lms2 ai saveetha in](https://github.com/user-attachments/assets/c3a0aa4b-50a8-42eb-a9a5-28fd28cb3e3a)


![Screenshot_9-3-2026_19051_lms2 ai saveetha in](https://github.com/user-attachments/assets/2b447777-dca6-4c10-b5da-35b6be3c83f7)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

