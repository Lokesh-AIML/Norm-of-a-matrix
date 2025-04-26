# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Get the input matrix using np.array()

Step 2: Find the 2-norm of the matrix using np.linalg.norm()

Step 3: Print the norm of the matrix in two decimal places.

Step 4: End the program.
## Program:
```Python
# Register No: 21222410029
# Developed By: Kamlesh.Y

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/b870735b-6662-479b-b06b-7d0cbe0bafa7)

### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/37b5aa0d-48b4-4a25-8a74-7553741c54ef)

### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/6ae0233a-e0e8-4cc6-b227-0971610422af)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
