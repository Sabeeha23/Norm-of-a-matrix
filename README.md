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
# Register No:23012003
# Developed By:Sabeeha Shaik
# 1-Norm of a Matrix
import numpy as np
array = np.array([[-1,3],[3,4],[1,7]])
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_matrix = "{:.2f}".format(ans)
print(norm_matrix)



# 2-Norm of a Matrix
import numpy as np
array1 = ([[1,2],[3,4]])
array2 = ([[-1,3],[3,-4],[1,7]])
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_matrix = "{:.2f}".format(ans)
print(norm_matrix)




# Infinity Norm of a Matrix
import numpy as np
array1 = ([[-1,3],[3,-4],[1,7]])
mat= np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_matrix = "{:.2f}".format(ans)
print(norm_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>![image](https://github.com/Sabeeha23/Norm-of-a-matrix/assets/150231876/5e001c7b-18f5-4b5c-b706-5965e33b65e7)

<br>
<br>

### 2-Norm of a Matrix
<br>![image](https://github.com/Sabeeha23/Norm-of-a-matrix/assets/150231876/c1a4000e-ebcc-48f8-9c4a-27ce32f54537)

<br>
<br>

### Infinity Norm of a Matrix
<br>![image](https://github.com/Sabeeha23/Norm-of-a-matrix/assets/150231876/3f761793-c9a1-40bb-a259-364f912244bd)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
