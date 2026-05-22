# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Start

Step 2: Define the matrix
A=[[1,2,3],[3,6,9]]

Step 3: Compare the rows of the matrix.

Step 4: Check whether the second row is a multiple of the first row.

Step 5:

If the second row is a multiple of the first row, set rank = 1.
Otherwise, set rank = 2.

Step 6: Display the rank.

Step 7: Stop.
## Program:
```
A = [[1,2,3],
     [3,6,9]]

# Check if second row is a multiple of first row
if (A[1][0]*A[0][1] == A[0][0]*A[1][1] and
    A[1][1]*A[0][2] == A[0][1]*A[1][2]):
    rank = 1
else:
    rank = 2

print(rank)
#DEVELOPED BY: ADHI SELVAKUMAR R
#REGISTER NO:212225220003
```

## Output:
<img width="1545" height="966" alt="Screenshot 2026-05-22 133050" src="https://github.com/user-attachments/assets/e889ce2c-9bda-4f0a-8307-d3470d9ef9f0" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

