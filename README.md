# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the necessary pyhton libraries
2. use the python library's inbuild fuction to perform the necessary tasks
3. store the final value in a variable
5. print the that variable

## Program:
(i) 'o find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: DEENESH RAJ G
RegisterNumber: 212225040056
*/

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by: DEENESH RAJ G
RegisterNumber: 21225040056
*/


## Output:
<img width="1333" height="779" alt="Screenshot 2026-03-20 144442" src="https://github.com/user-attachments/assets/0db8162a-134d-4cd3-9fac-dcf6f939ce42" />

<img width="1311" height="720" alt="Screenshot 2026-03-20 144454" src="https://github.com/user-attachments/assets/3c35173f-0546-4a7b-916e-6e609977dd89" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

