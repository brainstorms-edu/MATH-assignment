Task 1: Transpose of a Rectangular Matrix (Using Two Matrices)

In this task, you wrote a program to compute the transpose of a rectangular matrix.

Took a regular n × m matrix.

Created a new matrix of size m × n.

Filled it so that tMat[j][i] = mat[i][j].
OUTPUT-
Transpose of the matrix:
1 2 3 4
1 2 3 4
1 2 3 4
1 2 3 4

Task 2: Transpose of a Square Matrix (In-Place)

Here you implemented the in-place transpose of a square matrix.

Used only one matrix.

Swapped elements only above the diagonal.

Used:swap(mat[i][j], mat[j][i]);
OUTPUT-
In-place Transpose:
1 4 7
2 5 8
3 6 9

Task 3: Check if a Matrix is Symmetric
A matrix is symmetric if:
𝐴=𝐴𝑇
Took a square matrix as input.
Compared every element with its transposed position: 
if(mat[i][j] != mat[j][i])
INPUT-
Enter size of square matrix (N): 3
Enter elements of the matrix:
1 3 5
3 2 4
5 4 1
OUTPUT-
The matrix is symmetric.

Task 4: Check if a Matrix is Skew-Symmetric
A matrix is skew-symmetric
Created the transpose of the matrix.
Checked the skew condition:
if (mat[i][j] !=-transpose[i][j])
INPUT-
Enter size of square matrix (n): 3
Enter elements of the matrix:
0 5 -4
-5 0 1
4 -1 0
OUTPUT-
Transpose Matrix:
0 -5 4
5 0 -1
-4 1 0
The matrix is skew-symmetric.

Task 5: Matrix Addition (With User Input)
You wrote a program that:
Took two matrices from user input.
Added them element-wise:
c[i][j] = a[i][j] + b[i][j];
Enter number of rows: 2
Enter number of columns: 2
INPUT-
Enter elements of Matrix A:
2 5
1 7
Enter elements of Matrix B:
3 7
2 9
Output-
Resultant Matrix (A + B):
5 12
3 16

Task 6: Matrix Subtraction (With User Input)
Similar to addition, but you performed subtraction.
Took two matrices from user input.
Subtracted them element-wise.
Displayed the result.
INPUT-
Enter number of rows: 2
Enter number of columns: 2

Enter elements of Matrix A:
1 2
3 4

Enter elements of Matrix B:
1 2
4 5
OUTPUT-
Resultant Matrix (A - B):
0 0
-1 -1

Task 7: Matrix Multiplication (With User Input)
This task demonstrates true matrix multiplication.
Took input for matrix sizes and elements.
ensured the inner dimensions matched.
Used the triple nested loop:
c[i][j] += a[i][k] * b[k][j];
INPUT-
Enter rows of Matrix A: 2
Enter columns of Matrix A (and rows of Matrix B): 2
Enter columns of Matrix B: 2

Enter elements of Matrix A (2x2):
1 2
2 3

Enter elements of Matrix B (2x2):
1 2
2 2
OUTPUT-
Resultant Matrix (A ╫ B):
5 6
8 10


