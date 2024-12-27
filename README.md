# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

# 1-norm of matrix
    1. Get the input matrix using np.array()   
    2. Find the 1-norm of the matrix using np.linalg.norm(arr,1)
	3. Print the norm of the matrix in two decimal places.


# 2-norm of matrix
	1.Get the input matrix using np.array()   
    2.Find the 2-norm of the matrix using np.linalg.norm(arr,2)
	3.Print the norm of the matrix in two decimal places.

# Infinity Norm of a Matrix 
    1.Get the input matrix using np.array()   
    2.Find the infinity-norm of the matrix using np.linalg.norm(arr,np.inf)
	3.Print the norm of the matrix in two decimal places.

    

## Program:
```
# Register No:24008873
# Developed By:Junjar U
```
# 1-Norm of a Matrix
```
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)

```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: Junjar U
RegisterNumber: 24008873
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(f"{result:.2f}")

```
# Infinity Norm of a Matrix

```
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)

```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/0b3cb4d9-48a6-4531-ab1e-0e5b6898289b)

### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/5a3db68f-82b6-47e1-bbd3-87f227e66907)

### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/f69c0fec-9b3e-43a3-b927-094f908beb7b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
