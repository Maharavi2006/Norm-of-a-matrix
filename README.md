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

# Register No:212223230117
# Developed By:R.MAHALAKSHMI
```
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-17 105438](https://github.com/Maharavi2006/Norm-of-a-matrix/assets/154535981/96c16c7c-e376-422b-805c-d5f3c3e64fb3)


### 2-Norm of a Matrix

![Screenshot 2024-05-17 105454](https://github.com/Maharavi2006/Norm-of-a-matrix/assets/154535981/29eff721-1e0f-4263-ae27-082b3102a69a)

### Infinity Norm of a Matrix
![Screenshot 2024-05-17 105508](https://github.com/Maharavi2006/Norm-of-a-matrix/assets/154535981/740c2896-0415-4917-8e56-1e291c8483db)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
