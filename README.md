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
# Register No:24900982
# Developed By: SHEIK FAIZAL S
# 1-Norm of a Matrix
```
```
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)
```

```
#2-Norm of a Matrix
import numpy as np
matrix=(eval(input()))
l2_norm=np.linalg.norm(matrix,2)
print(f"{l2_norm:.2f}")
```


```
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
l2_norm=np.linalg.norm(a,np.inf)
print(l2_norm)

```
## Output:
### 1-Norm of a Matrix
![alt text](image.png)

### 2-Norm of a Matrix
![alt text](image-1.png)

### Infinity Norm of a Matrix
![alt text](image-2.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
