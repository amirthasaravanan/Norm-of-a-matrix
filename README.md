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
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

![Screenshot (2017)](https://github.com/user-attachments/assets/c7c712c3-e1a2-4ab5-bada-9876eb2667c5)


### 2-Norm of a Matrix
<br>
<br>
<br>

![Screenshot (2018)](https://github.com/user-attachments/assets/65af42e2-7bc7-4550-ba4a-b163383f604e)


### Infinity Norm of a Matrix
<br>
<br>
<br>

![Screenshot (2020)](https://github.com/user-attachments/assets/d13b9ac8-c5d2-4930-b6dd-6936c2eeab47)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
