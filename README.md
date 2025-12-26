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
# Register No:25005672
# Developed By: balaji t
# 1-Norm of a Matrix

# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)


# 2-Norm of a Matrix

Program to find 2-norm of a matrix.
Developed by: BALAJI
RegisterNumber: 25005672
'''
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")



# Infinity Norm of a Matrix


# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)


```
## Output:
### 1-Norm of a Matrix
<br><img width="1103" height="891" alt="image" src="https://github.com/user-attachments/assets/dc4d433e-e2f7-42a6-af2a-eb0fb593d802" />

<br>
<br>

### 2-Norm of a Matrix
<br<img width="1249" height="728" alt="image" src="https://github.com/user-attachments/assets/e4ea5a09-5ee7-476b-8cfd-67fb5a9f8f55" />
>
<br>
<br>

### Infinity Norm of a Matrix
<br>
<br><img width="1199" height="571" alt="image" src="https://github.com/user-attachments/assets/795efaa4-bb50-4065-b62b-22614525e710" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
