# DATE:
# EX-07 Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
### 1-Norm of a Matrix
```
# Register No: DEEPIKA R
# Developed By: 212223230038
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/d4ed8b0e-8899-4b5e-b976-c5c91550e117)

# 2-Norm of a Matrix
```
# Register No: DEEPIKA R
# Developed By: 212223230038
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/cbd2bc4b-c88e-4aab-b1be-a07994e37f09)

# Infinity Norm of a Matrix
```
# Register No: DEEPIKA R
# Developed By: 212223230038
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/53bd1329-4090-4293-ad88-8ffd925b7505)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
