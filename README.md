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
```
# 1-Norm of a Matrix
'''
program to find 1-Norm of a matrix.
Developed by:SHARAN.G
RegisterNumber:212223230203
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:SHARAN.G
RegisterNumber:0212223230203
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))





# Infinity Norm of a Matrix
'''
program to find the Infinity of a matrix
developed by:SHARAN.G
RegisterNumber:212223230203
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-12-26 152936](https://github.com/Sharan1731/Norm-of-a-matrix/assets/144980172/ce363178-b1e5-4af6-900d-0df7ec3f682d)


### 2-Norm of a Matrix

![Screenshot 2023-12-26 153038](https://github.com/Sharan1731/Norm-of-a-matrix/assets/144980172/8be1ac5e-72a9-4413-84f9-20fd443faa5d)


### Infinity Norm of a Matrix

![Screenshot 2023-12-26 153124](https://github.com/Sharan1731/Norm-of-a-matrix/assets/144980172/34926680-0564-4a1b-990d-3ed226dd73ab)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
