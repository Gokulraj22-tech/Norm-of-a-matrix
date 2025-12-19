# Norm of a matrix
# Aim:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
# Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
# Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
# Program:
```
Register No:25017714
Developed By: GOKULRAJ K
```
```Python
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)

# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")

# 3-Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```

# Output:
## 1-Norm of a Matrix:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b2d7b341-9020-4b1b-bcbb-bc8d82de811d" />


## 2-Norm of a Matrix
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b4c49770-0557-471d-bcde-813581b09f57" />


## Infinity Norm of a Matrix
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/03bcf39c-8359-4a1c-b630-45184f27a3d0" />

# Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
