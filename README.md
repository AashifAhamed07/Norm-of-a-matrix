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
# Register No: 212225040004
# Developed By: Aashif Ahamed S
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="578" height="187" alt="Screenshot 2026-02-07 085131" src="https://github.com/user-attachments/assets/062a4771-db97-4041-89e3-8cdf60b72511" />
<br>
<br>
<br>

### 2-Norm of a Matrix

<img width="585" height="239" alt="Screenshot 2026-02-07 085156" src="https://github.com/user-attachments/assets/03fa8c26-0733-4252-9d5b-0024a2b8314c" />
<br>
<br>
<br>

### Infinity Norm of a Matrix

<img width="565" height="188" alt="Screenshot 2026-02-07 085230" src="https://github.com/user-attachments/assets/bf1ad226-e002-41f3-977c-083e60975f7d" />
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
