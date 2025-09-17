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

<img width="725" height="231" alt="Screenshot 2025-09-17 060943" src="https://github.com/user-attachments/assets/0d9d5ca8-32af-4724-8f75-fc8dc956e642" />

### 2-Norm of a Matrix
<img width="611" height="274" alt="Screenshot 2025-09-17 060949" src="https://github.com/user-attachments/assets/624393e8-9f9e-4e32-8bfa-4af306e94e84" />


### Infinity Norm of a Matrix
<img width="688" height="217" alt="Screenshot 2025-09-17 060953" src="https://github.com/user-attachments/assets/7e1a18de-dd17-4ba6-bf47-2aec1e661777" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
