# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Program-1
 1. Get the input matrix using np.array()
 2. Find the 1-norm of the matrix using np.linalg.norm()
 3. Print the norm of the matrix in two decimal places.
	

Program-2
 
 1. Get the input matrix using np.array()
 2. Find the 2-norm of the matrix using np.linalg.norm()
 3. Print the norm of the matrix in two decimal places.

Program-3
1. Get the input matrix using np.array()   
2. Find the Infinity-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

## Program:

# 1-Norm matrix
```
# Register No:242224230135
# Developed By:LAAVANYA.R
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(round(result))

```


# 2-Norm of a Matrix
```
Developed by: LAAVANYA.R
RegisterNumber: 242224230135

import numpy as np
arr=np.array(eval(input()))
r=np.linalg.norm(arr,2)
print(round(r,2))

```
# Infinity Norm of a Matrix

```
Developed by: LAAVANYA.R
RegisterNumber: 242224230135

import numpy as np
arr=np.array(eval(input()))
r=np.linalg.norm(arr,np.inf)
print(round(r,2))


```
## Output:

### 1-Norm of a Matrix
<img width="1244" height="845" alt="Screenshot 2025-09-25 231159" src="https://github.com/user-attachments/assets/f797cb54-f594-4485-86bc-5ca94dd0149c" />


### 2-Norm of a Matrix
<img width="1249" height="857" alt="Screenshot 2025-09-25 231214" src="https://github.com/user-attachments/assets/fb5b2940-00ee-49a2-aeff-0d401bc216b7" />


### Infinity Norm of a Matrix
<img width="1237" height="882" alt="Screenshot 2025-09-25 231225" src="https://github.com/user-attachments/assets/d9c67b98-cbc9-4194-8e7c-fd004d8c30be" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
