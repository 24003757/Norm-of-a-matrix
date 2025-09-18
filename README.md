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
# Register No: 212224240184
# Developed By: Vinolia Alaina . R
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
<img width="1215" height="983" alt="Screenshot 2025-09-18 090447" src="https://github.com/user-attachments/assets/a85ce54a-71c9-4963-a3ff-d8ad2ca4139c" />
### 2-Norm of a Matrix
<img width="1065" height="985" alt="Screenshot 2025-09-18 090458" src="https://github.com/user-attachments/assets/a8beee03-fb7a-4eef-9fa1-3e6a626e2f18" />
### Infinity Norm of a Matrix
<img width="1099" height="959" alt="Screenshot 2025-09-18 090505" src="https://github.com/user-attachments/assets/987f7324-927e-4222-82d8-8bd349bedfb5" />
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
