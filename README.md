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
# Register No:26011506
# Developed By:Nandhana S
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
<img width="1250" height="825" alt="Screenshot 2026-11-12 090552" src="https://github.com/user-attachments/assets/7dc0b96e-429c-401b-b1a0-e6207a010e92" />

### 2-Norm of a Matrix
<img width="1248" height="866" alt="Screenshot 2026-11-12 090617" src="https://github.com/user-attachments/assets/e0e16fc1-5352-483b-ac17-e31487c71bf6" />


### Infinity Norm of a Matrix
<img width="1227" height="787" alt="Screenshot 2026-11-12 090653" src="https://github.com/user-attachments/assets/932b2cb5-bc53-4c9e-8871-ed69b6d0a235" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
