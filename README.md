# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library.
### Step 2: Define the matrix.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix.
## Program:

# Program to find the rank of a matrix
# Using NumPy library

import numpy as np

# Define matrix
A = np.array([[1, 2, 3],
              [4, 5, 6],
              [7, 8, 9]])

# Find rank
rank = np.linalg.matrix_rank(A)

# Display result
print("Matrix:")
print(A)

print("\nRank of the matrix is:", rank)

## Output:

Matrix:
[[1 2 3]
 [4 5 6]
 [7 8 9]]

Rank of the matrix is: 2

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

