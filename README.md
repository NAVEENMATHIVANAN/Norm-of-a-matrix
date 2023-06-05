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
# Register No: NAVEEN KUMAR M
# Developed By: 212222110028
# 1-Norm of a Matrix

import numpy as np 
mat=np.array (eval (input () )) 
ans=np.linalg.norm(mat, 1) 
norm_of_matrix="{:.2f}".format(ans) 
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/NAVEENMATHIVANAN/Norm-of-a-matrix/assets/119394582/ef705231-57f8-43be-87d2-00e03f3879a3)


### 2-Norm of a Matrix
![image](https://github.com/NAVEENMATHIVANAN/Norm-of-a-matrix/assets/119394582/95dee199-d8db-41bf-bb38-9683375a5d0c)


### Infinity Norm of a Matrix

![image](https://github.com/NAVEENMATHIVANAN/Norm-of-a-matrix/assets/119394582/baa33a1e-d67a-4721-8d19-13ed7c7ee461)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
