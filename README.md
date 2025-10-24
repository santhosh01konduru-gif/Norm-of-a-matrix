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
# Register No:25011489
# Developed By:konduru santhosh
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,1)
print(norm)
# 2-Norm of a Matrix
import numpy as np
a = np.array(eval(input()))
norm = np.linalg.norm(a,2)
print(f"{norm:.2f}")
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,np.inf)
print(f"{norm:.2f}")
```
## Output:
### 1-Norm of a Matrix
<br><img width="818" height="485" alt="image" src="https://github.com/user-attachments/assets/e24fca4c-47f4-45ed-ab58-906adee5e7d1" />

### 2-Norm of a Matrix
<br><img width="819" height="469" alt="image" src="https://github.com/user-attachments/assets/95cb4fe9-3130-40e6-b5d9-6c4acd0891be" />

### Infinity Norm of a Matrix
<br><img width="822" height="473" alt="image" src="https://github.com/user-attachments/assets/d51b0b39-a1e3-48b5-9008-0ed56d442859" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
