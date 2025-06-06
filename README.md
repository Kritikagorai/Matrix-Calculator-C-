
🧮 Matrix Calculator (C++)

This is a menu-driven C++ program that performs basic matrix operations on two matrices of user-defined size.


---

✅ Features

Matrix Addition

Matrix Subtraction

Matrix Multiplication

Option to Exit



---

📥 Input

Number of rows and columns for the matrices (up to 10x10)

Elements of two matrices A and B of size [rows][columns]



---

📤 Output

Result of the selected operation (Addition, Subtraction, Multiplication)



---

🖥️ How It Works

1. User inputs dimensions and elements for two matrices.


2. Menu is displayed:

1. ADDITION
2. SUBTRACTION
3. MULTIPLICATION
4. EXIT


3. Based on the user's choice:

Performs addition: C[i][j] = A[i][j] + B[i][j]

Performs subtraction: C[i][j] = A[i][j] - B[i][j]

Performs multiplication using triple loop: C[i][j] += A[i][k] * B[k][j]

Or exits the program.





---

⚠️ Notes

This version assumes both matrices are of the same size.

Multiplication is only allowed for square matrices (e.g., 2x2, 3x3).

Maximum allowed size is 10x10.



---

📌 Sample

Input:

Rows: 2
Columns: 2

Matrix A:
1 2
3 4

Matrix B:
5 6
7 8

Output (Addition):

6 8
10 12


--
