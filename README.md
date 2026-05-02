# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.solve(), we can find the solutions.

Step 4:
End the program 

## Program:
```

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eig_values,eig_vector=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vector))
```
## Output:
<img width="1421" height="151" alt="image" src="https://github.com/user-attachments/assets/0555b181-5fa9-4107-ab34-6d7522a2748f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
