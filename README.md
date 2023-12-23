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
# Register No:singamala venkata sai kumar reddy
# Developed By:23004205
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))


# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: singamala venkata sai kumar reddy
RegisterNumber: 23004205
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))




# Infinity Norm of a Matrix
'''
program to find infinity-Norm of matrix
Developed by:singamala venkata sai kumar reddy
reference no:23004205

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))


```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-12-23 160237](https://github.com/23004205/Norm-of-a-matrix/assets/138971114/943ae508-c154-4b71-bb1f-9638f0d7bf46)



### 2-Norm of a Matrix


![Screenshot 2023-12-23 160641](https://github.com/23004205/Norm-of-a-matrix/assets/138971114/eb909937-c463-4aed-8203-24affdefa750)



### Infinity Norm of a Matrix

![Screenshot 2023-12-23 160715](https://github.com/23004205/Norm-of-a-matrix/assets/138971114/85efb81c-19e6-4d85-8090-a54a4203e271)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
