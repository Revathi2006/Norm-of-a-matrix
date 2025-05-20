# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
Python program to find the 1-norm, 2-norm and infinity norm of the matrix
# Register No:212224230228
# Developed By:Revathi.S
```


# 1-Norm of a Matrix


```
import numpy as np

m=np.array(eval(input()))

a=np.abs(m)

s=np.sum(a,axis=0)

ma=np.max(s)

print(ma)

```






# 2-Norm of a Matrix


```
import numpy as np

mat=np.array(eval(input()))

l2=np.linalg.norm(mat,2)

print(f"{l2:.2f}")
```


# Infinity Norm of a Matrix

```

import numpy as np

mat=np.array(eval(input()))

infinity=np.linalg.norm(mat,np.inf)

print(f"{infinity:.2f}")




````
## Output:



### 1-Norm of a Matrix


![Screenshot 2025-05-20 121014](https://github.com/user-attachments/assets/373d83b9-07e2-4d48-bc99-6675f431f2be)



### 2-Norm of a Matrix


![Screenshot 2025-05-20 121024](https://github.com/user-attachments/assets/defd746d-1586-4e07-b24b-89056a82191e)


### Infinity Norm of a Matrix



![Screenshot 2025-05-20 121035](https://github.com/user-attachments/assets/4f6bdc29-bda8-4427-a63b-6a4c0047a51d)




## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
