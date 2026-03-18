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
# Register No:25016067
# Developed By:Madhumitha V
# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(norm)


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Madhumitha V
RegisterNumber: 25016067
'''
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")



# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,np.infty)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<img width="1402" height="486" alt="Screenshot 2026-03-18 112255" src="https://github.com/user-attachments/assets/f91e9864-ac2f-46a6-9a41-1855f63d1cfa" />

<img width="1229" height="341" alt="Screenshot 2026-03-18 112133" src="https://github.com/user-attachments/assets/eda155a1-2fac-47d2-90c5-cce1790af467" />



### 2-Norm of a Matrix
![WhatsApp Image 2026-03-18 at 11 24 17 AM](https://github.com/user-attachments/assets/34354801-1ddc-478a-817f-0f628add73d1)

<img width="1229" height="385" alt="Screenshot 2026-03-18 112150" src="https://github.com/user-attachments/assets/8853812a-3a1e-4792-ad53-79406ed8a602" />



### Infinity Norm of a Matrix
![WhatsApp Image 2026-03-18 at 11 17 41 AM](https://github.com/user-attachments/assets/fc6426df-7d42-4224-93d3-b63e30a02b49)

<img width="1231" height="334" alt="Screenshot 2026-03-18 112202" src="https://github.com/user-attachments/assets/1acd4453-1681-44a7-9a49-cf05455dd951" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
