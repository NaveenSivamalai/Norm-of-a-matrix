# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: naveen s
# Developed By: 212222110030
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))


# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/NaveenSivamalai/Norm-of-a-matrix/assets/123792574/a592f993-4956-4550-92ce-76247499d112)


### 2-Norm of a Matrix
![image](https://github.com/NaveenSivamalai/Norm-of-a-matrix/assets/123792574/06dbb4c0-3baa-4872-adab-d531379694c9)


### Infinity Norm of a Matrix
![image](https://github.com/NaveenSivamalai/Norm-of-a-matrix/assets/123792574/50b6c8d7-bc17-41d0-9a81-1e39f2764baa)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
