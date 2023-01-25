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
# Register No: 22008605
# Developed By:mahesh raj purohit
# 1-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: mahesh raj purohit
RegisterNumber: 22008605
'''
import numpy as np
a=np.array(eval(input()))
n = np.linalg.norm(a,1)
print("{:.2f}".format(n))




# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: mahesh raj purohit
RegisterNumber: 22008605
'''
import numpy as np
a=np.array(eval(input()))
n = np.linalg.norm(a,2)
print("{:.2f}".format(n))




# Infinity Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: mahesh raj purohit
RegisterNumber: 22008605
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Screenshot from 2023-01-25 23-09-18](https://user-images.githubusercontent.com/118749665/214641339-1778bb59-7e42-401e-97bd-a67f8207f9ea.png)


### 2-Norm of a Matrix
![Screenshot from 2023-01-25 23-10-07](https://user-images.githubusercontent.com/118749665/214641422-12f8d3b8-6f59-4527-be7e-9128f6c2344e.png)


### Infinity Norm of a Matrix
![Screenshot from 2023-01-25 23-10-07](https://user-images.githubusercontent.com/118749665/214641461-0d9dc72d-8653-4df4-90b0-eb5d67245ee9.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
