# LU Decomposition
# AIM:
To write a program to find the LU Decomposition of a matrix.

# Equipments Required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
# Algorithm
1.Import the numpy module to use the built-in functions for calculation.

2.From scipy.linalg module import the lu funtion.

3.Get inputs from the user and assign the values in np.array().

4.Using the lu() function,we can find the L and U matrix.

5.Print the obtained values.

6.End the program.

# Program:
# (i) To find the L and U matrix

Program to find L and U matrix using LU decomposition.
``` 


import numpy as np
from scipy.linalg import lu
a=eval(input()) 
P,L,U=lu(a) 
print(L)
print(U)
``` 
# (ii) To find the LU Decomposition of a matrix

Program to solve a matrix using LU decomposition.
``` 

import numpy as np
from scipy. linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
``` 
# OUTPUT1:

![image](https://github.com/naren2704/LU-Decomposition/assets/118706984/b0b005e8-a1ed-4b43-84f0-272ad2de12ed)

# Output2:
![image](https://github.com/naren2704/LU-Decomposition/assets/118706984/0c0c5ab9-a630-458a-bc95-d00a7b9ba18d)


# Result:
Thus the program to solve the matrix using LU Decomposition is written and verified using python programming.
