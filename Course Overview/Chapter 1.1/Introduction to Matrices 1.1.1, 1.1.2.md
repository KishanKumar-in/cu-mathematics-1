# Introduction to Matrices 1.1.1, 1.1.2

The topic is associated with the following course outcome:

CO1 : Define the fundamentals of matrices, vector spaces and differential equations.

##

##                                                                 Matrices

A matrix represents a collection of numbers arranged in an order of rows and columns. It is necessary to enclose the elements of a matrix in parentheses or brackets.

A matrix with 9 elements is shown below.

This Matrix [M] has 3 rows and 3 columns. Each element of matrix [M] can be referred to by its row and column number. For example, a23=6

## Order of a Matrix:

The order of a matrix is defined in terms of its number of rows and columns.

Order of a matrix = No. of rows ×No. of columns

Therefore Matrix [M] is a matrix of order 3 × 3.

## Transpose of a Matrix:

The transpose [M]T of an m x n matrix [M] is the n x m matrix obtained by interchanging the rows and columns of [M].

if A= [aij] mxn , then AT = [bij] nxm where bij = aji

## Properties of transpose of a matrix:

·        (AT)T = A

·        (A+B)T = AT + BT

·        (AB)T = BTAT

## Singular and Nonsingular Matrix:

1.     Singular Matrix: A square matrix is said to be singular matrix if its determinant is zero i.e. |A|=0

2.     Nonsingular Matrix: A square matrix is said to be non-singular matrix if its determinant is non-zero.

## Square Matrix

A square Matrix has as many rows as it has columns. i.e. no of rows = no of columns.

## Symmetric matrix

A square matrix is said to be symmetric if the transpose of original matrix is equal to its original matrix. i.e. (AT) = A.

## Skew-symmetric

A skew-symmetric matrix is a square matrix whose transpose equals its negative .i.e. (AT) = -A.

## Diagonal Matrix

A diagonal matrix is a matrix in which the entries outside the main diagonal are all zero. The term usually refers to square matrices.

## Identity Matrix

A square matrix in which all the elements of the principal diagonal are ones and all other elements are zeros. Identity matrix is denoted as I.

## Orthogonal Matrix

A matrix is said to be orthogonal if AAT = ATA = I

## Idempotent Matrix

A matrix is said to be idempotent if A2 = A

## Involutory Matrix

A matrix is said to be Involutory if A2 = I.

## Adjoint of a square matrix:

## Properties of Adjoint:

1.     A(Adj A) = (Adj A) A = |A| In

2.     Adj(AB) = (Adj B).(Adj A)

3.     |Adj A|= |A|n-1

4.     Adj(kA) = kn-1 Adj(A)

## Trace of a matrix :

Let A=[aij] nxn is a square matrix of order n, then the sum of diagonal elements is called the trace of a matrix which is denoted by tr(A). tr(A) = a11 + a22 + a33+ ……….+ ann. Remember trace of a matrix is also equal to the sum of eigen value of the matrix.

For example:

## Properties of trace of matrix:

Let A and B be any two square matrices of order n, then

1.     tr(kA) = k tr(A) where k is a scalar.

2.     tr(A+B) = tr(A)+tr(B)

3.     tr(A-B) = tr(A)-tr(B)

4.     tr(AB) = tr(BA)

##

Real-life Applications

## 🔢 1. Computer Graphics

Concepts Used: Matrix multiplication, transformation matrices

Application: Rotating, scaling, and translating images or 3D models in games, movies, and simulations.

Example: A transformation matrix can rotate a 2D image around a point using matrix multiplication.

## 🧠 2. Machine Learning & Artificial Intelligence

Concepts Used: Matrix multiplication, dot products, identity matrices

Application: Training neural networks, representing datasets, and computing weights in layers.

Example: In a neural network, the input data and weights are often stored as matrices for efficient computation.

## 📈 3. Economics & Business (Input-Output Models)

Concepts Used: Matrix equations, inverse matrices

Application: Leontief input-output model to study interdependencies in economic sectors.

Example: How much of each product needs to be produced to satisfy certain consumption requirements.

## 🔧 4. Engineering Systems (Control Systems)

Concepts Used: System of linear equations, state-space representation

Application: Representing dynamic systems and analyzing their behavior.

Example: Using matrices to describe an electrical circuit or a mechanical system.

## 🌐 5. Cryptography

Concepts Used: Matrix inversion, modular arithmetic

Application: Encrypting and decrypting messages.

Example: The Hill Cipher uses matrix multiplication and inverse matrices for encryption and decryption.

## Extra Study Material Links:

- https://www.geeksforgeeks.org/introduction-to-matrices/

- https://archive.nptel.ac.in/courses/111/108/111108157/

Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing