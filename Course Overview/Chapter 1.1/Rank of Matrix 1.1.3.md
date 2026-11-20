# Rank of Matrix 1.1.3

## The topic is associated with the following course outcomes:

## CO1

## Define the fundamentals of matrices, infinite series and differential equations.

## CO2

## Identify and distinguish the types of matrices, infinite series and  differential equations.

##

##                                                                         Rank of a matrix

Rank of matrix is the number of non-zero rows in the row reduced form or the maximum number of independent rows or the maximum number of independent columns.

Let A be any mxn matrix and it has square sub-matrices of different orders. A matrix is said to be of rank r, if it satisfies the following properties:

1.    It has at least one square sub-matrices of order r who has non-zero determinant.

2.    All the determinants of square sub-matrices of order (r+1) or higher than r are zero.

3.    Rank is denoted as P(A).

if A is a non-singular matrix of order n, then rank of A = n i.e. P(A) = n.

## Properties of rank of a matrix:

##

1.    If A is a null matrix then P(A) = 0 i.e. Rank of null matrix is zero.

2.    If In is the nxn unit matrix then P(A) = n.

3.    Rank of a matrix A mxn, P(A) ≤ min(m,n). Thus P(A) ≤m and P(A) ≤ n.

4.    P(A nxn ) = n if |A| ≠ 0

5.    If P(A) = m and P(B)=n then P(AB) ≤ min(m,n).

6.    If A and B are square matrices of order n then P(AB) ? P(A) + P(B) – n.

7.    If Am×1 is a non-zero column matrix and B1×n is a non-zero row matrix then P(AB) = 1.

8.    The rank of a skew symmetric matrix cannot be equal to one.

##       Example:

##

##         Example:

The rank of a matrix is a fundamental concept in linear algebra with many important real-world applications. It essentially tells us the number of linearly independent rows or columns in a matrix, which is critical for understanding the solutions to systems of equations, data dimensions, and information redundancy.

Here are key applications based on the rank of a matrix:

## 📐 1. Solving Systems of Linear Equations

Concept Used: Rank to determine the number of solutions (unique, infinite, or none).

Application: Used in engineering, physics, and economics to solve systems of constraints.

Example: If the rank of the coefficient matrix equals the rank of the augmented matrix and equals the number of variables, the system has a unique solution.

## 🧮 2. Linear Dependence and Data Redundancy

Concept Used: Rank = Number of linearly independent vectors.

Application: Detecting redundant data or equations in scientific computations or datasets.

Example: In data science, identifying duplicate features or unnecessary data points in high-dimensional data.

## 🧠 3. Machine Learning & Data Science (Dimensionality Reduction)

Concept Used: Rank to determine intrinsic dimensionality of data.

Application: Used in techniques like Principal Component Analysis (PCA) to reduce the number of variables.

Example: Reducing a dataset from 1000 variables to only the top 10 that capture the most variance (effective rank).

## 🎥 4. Image Compression

Concept Used: Low-rank approximation of matrices

Application: Storing images efficiently by removing unnecessary data.

Example: Using Singular Value Decomposition (SVD), an image matrix can be approximated by a lower-rank matrix, reducing storage size without significant quality loss.

##

## 🔐 5. Cryptography

Concept Used: Full-rank matrices in encryption/decryption

Application: Ensuring invertibility of encryption matrices.

Example: The Hill Cipher only works if the encryption matrix is full-rank (i.e., invertible over modular arithmetic).

##

##

## Extra Study Material Links:

Rank of a Matrix: Definition, Properties, and Formula | GeeksforGeeks

NPTEL :: Mathematics - NOC:Matrix Analysis with Applications

Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing