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
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))




# Infinity Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))




```
## Output:
### 1-Norm of a Matrix

![ex1](https://user-images.githubusercontent.com/121303741/215315132-00810218-bc46-4e2e-9280-fc94c8862a5b.png)

### 2-Norm of a Matrix

![ex2](https://user-images.githubusercontent.com/121303741/215315140-c60d8943-479b-4443-a667-778b08725eac.png)

### Infinity Norm of a Matrix
![ex3](https://user-images.githubusercontent.com/121303741/215315150-b9a71e84-942a-4737-8d68-8dfd37447a32.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
