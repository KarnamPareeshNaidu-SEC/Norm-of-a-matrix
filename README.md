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
#Regestration number: 212225230129
#Developed by: KARNAM PAREESH NAIDU


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}" .format(ans)
print(norm)




# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: KARNAM PAREESH NAIDU
RegisterNumber: 212225230129
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}" .format(ans)
print(norm)


# Infinity Norm of a Matrix

#reg.no: 212225230129
#developed by: KARNAM PAREESH NAIDU
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}" .format(ans)
print(norm)



```
## Output:
### 1-Norm of a Matrix
<img width="924" height="775" alt="image" src="https://github.com/user-attachments/assets/775651b2-2ac4-4a3b-ab26-906ed434a4bc" />


### 2-Norm of a Matrix
<img width="920" height="827" alt="image" src="https://github.com/user-attachments/assets/2b94507e-c2b4-4b91-ba97-08a489a32256" />


### Infinity Norm of a Matrix
<img width="904" height="775" alt="image" src="https://github.com/user-attachments/assets/5bce9057-fc9c-41b1-a7ab-93c8ae19a830" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
