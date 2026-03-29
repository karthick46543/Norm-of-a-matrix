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
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")



# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")



# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm3=np.linalg.norm(A,np.inf)


```
## Output:
### 1-Norm of a Matrix
-<img width="404" height="106" alt="image" src="https://github.com/user-attachments/assets/84bbb6d7-8aba-4baf-95ca-4499b4378d9f" />


### 2-Norm of a Matrix
<img width="371" height="101" alt="image" src="https://github.com/user-attachments/assets/99380523-c770-4fcb-857d-de81d88afc88" />


### Infinity Norm of a Matrix
<img width="298" height="88" alt="image" src="https://github.com/user-attachments/assets/ad215d66-2efa-4f48-a62b-988302e1e922" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
