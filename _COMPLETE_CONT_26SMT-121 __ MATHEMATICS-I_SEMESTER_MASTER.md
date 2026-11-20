# CONT_26SMT-121 __ MATHEMATICS-I - COMPLETE SEMESTER MASTER NOTES

This document contains all lecture notes and slides across all units.

---

# Chapter 1.1 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Echelon form of Matrix 1.1.4
# Echelon form of Matrix 1.1.4

## The topic is associated with the following course outcomes:

## CO1

## Define the fundamentals of matrices, infinite series and differential equations.

## CO2

## Identify and distinguish the types of matrices, infinite series and  differential equations.

##

##

## The echelon form of a matrix (particularly the row echelon form and reduced row echelon form) plays a key role in many applications in linear algebra and beyond. Here are the main applications of echelon forms of matrices:

## 🔹 1. Solving Systems of Linear Equations

## Purpose: To determine whether a system has a unique solution, infinitely many solutions, or no solution.

Method: Convert the augmented matrix of the system into row echelon form (REF) or reduced row echelon form (RREF) using elementary operations.

## 🔹 2. Determining Rank of a Matrix

## Purpose: The rank tells you the dimension of the row space or column space (number of linearly independent rows or columns).

Method: The number of non-zero rows in the row echelon form of a matrix equals its rank.

## 🔹 3. Finding Inverses of Matrices

## Purpose: Inverting a matrix is critical for solving systems

Ax=b when A is square and invertible.

Method: Augment matrix

## A with the identity matrix

I, then row reduce: [A∣I]→[I∣A-1]

## 🔹 4. Checking Linear Independence

## Purpose: To determine whether vectors (rows or columns) are linearly independent.

Method: Put the matrix whose columns are the vectors into echelon form and count the pivot columns.

## 🔹 5. Solving Homogeneous Systems

## Purpose: Finding the null space of a matrix (solution set of Ax=0).

Method: Reduce A to REF to identify the free variables and express the solution set.

##

##

## Extra Study Material Links:

## Rank of a Matrix: Definition, Properties, and Formula | GeeksforGeeks

NPTEL :: Mathematics - NOC:Matrix Analysis with Applications

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Introduction to Matrices 1.1.1, 1.1.2
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

---


### Normal form of Matrix 1.1.5
# Normal form of Matrix 1.1.5

## The topic is associated with the following course outcomes:

## CO1

## Define the fundamentals of matrices, infinite series and differential equations.

## CO2

## Identify and distinguish the types of matrices, infinite series and  differential equations.

##

##

##

## Here are some key Applications based on the normal forms of matrices:

## 🔹 1. Diagonalization of Matrices

## 📌 Application: Simplifying Matrix Computations

Purpose: To simplify powers of matrices and exponentiation (e.g.,

AnA^n

,

eAe^A

).

Method: Diagonalize

AA

A as

A=PDP−1A = PDP^{-1}

, where

DD

is a diagonal matrix of eigenvalues.

Used In: Solving linear differential equations, Markov chains, and dynamic systems.

## 🔹 2. Jordan Normal Form

## 📌 Application: Solving Systems with Non-Diagonalizable Matrices

Purpose: A generalized diagonal form useful when a matrix isn't diagonalizable.

Method:

A=PJP−1A = PJP^{-1}

, where

JJ

is the Jordan form.

Used In:

Computing matrix functions (e.g.,

eAe^A

)

Stability analysis in control theory

Theoretical understanding of linear transformations

## 🔹 3. Hermite Normal Form (HNF)

## 📌 Application: Integer Linear Systems

Purpose: Simplify and solve systems of linear equations with integer coefficients.

Used In:

Cryptography

Integer programming

Computer algebra systems

##

## 🔹 4. Spectral Theorem and Normal Matrices

## 📌 Application: Quantum Mechanics and Functional Analysis

Purpose: For normal matrices (satisfying

AA∗=A∗AAA^* = A^*A

), there exists an orthonormal basis of eigenvectors.

Used In:

Quantum mechanics (Hermitian matrices represent observables)

Principal Component Analysis (PCA)

Signal processing

## 🔹 5. Canonical Forms in Control Theory

## 📌 Application: System Analysis and Design

Forms:

Controllable canonical form

Observable canonical form

Jordan or diagonal form of state-space matrices

Used In:

Simplifying analysis of dynamic systems

Designing controllers and observers

##

## Extra Study Material Links:

Rank of a Matrix: Definition, Properties, and Formula | GeeksforGeeks

https://ma202linearalgebra.files.wordpress.com/2020/11/l6_rank-of-matrix-by-normal-form.pdf

Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Rank of Matrix 1.1.3
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

---


## 🖥️ PRESENTATION SLIDES


# Chapter 1.1 - All Lecture Slides Text


## ch-1
### Slide 1
- UNIVERSITY INSTITUTE OF
- UIE
- Engineering Foundations-
- 1
- to 5
- Bachelor of Engineering
- All Branches
- / SEMESTER-1
- Mathematics-I
- (
- 26SMT-121
- )
- Unit
- No.
- 1
- Chapter No.
- 1
- Topic
- :
- Basics of Matrices
- Shivani
- Bansal and E5471                                                       Assistant Professor
- Academic Session
- 2026-27
- ODD Semester Jul-Dec
- 2026

### Slide 2
- Learning Objectives
- To
- understand the basic concept of matrices along with various types
- .
- 2. To
- understand the concept of rank of a
- matrix
- 1

### Slide 3
- Basics of Matrices
- Topic 1
- . Concept of Matrix
- Topic 2
- . Types of Matrices
- Topic 3
- . Rank of Matrices
- Figure-1
- source (google)
- 2

### Slide 4
- Concept of Matrix
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 3
- A matrix is an ordered rectangular array of elements arranged in horizontal rows and vertical columns.
- The entries of a matrix , called elements are scalar quantities which are commonly numbers but can also be functions , operators or matrices itself (called sub-matrices). For example:
- ORDER of a Matrix
- : A matrix having m rows and n columns is called a matrix of order m X n.
- In the above example, the matrix if of the order 3 X 3

### Slide 5
- Types
- of
- Matrices
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 4
- The various types of matrices are as follows
- :
- ROW MATRIX
- : A matrix having only one row is known as row matrix
- 1
- 2
- 3
- 1
- 𝑋
- 3
- COLUMN MATRIX:
- A matrix having only one column is known as column matrix
- 1
- 2
- 3
- 3
- 𝑋
- 1
- SQUARE MATRIX:
- A matrix having equal number of rows and columns is known as square matrix
- 𝟏
- 𝟒
- 𝟓
- 𝟑
- 𝟔
- −
- 𝟐
- −
- 𝟔
- 𝟗
- 𝟓
- 𝟑
- 𝑿
- 𝟑
- RECTANGULAR MATRIX:
- A matrix where the number of row and columns are unequal is said to be a rectangular matrix.
- 𝟏
- 𝟎
- 𝟕
- 𝟒
- 𝟓
- −
- 𝟏
- 𝟐
- 𝑿
- 𝟑

### Slide 6
- Types
- of
- Matrices
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 5
- DIAGONAL MATRIX:
- A square matrix is said to be a diagonal matrix if all its non diagonal elements are zero.
- 𝟏
- 𝟎
- 𝟎
- 𝟎
- 𝟔
- 𝟎
- 𝟎
- 𝟎
- 𝟓
- 𝟑
- 𝑿
- 𝟑
- SCALAR MATRIX:
- A diagonal matrix is said to be a scalar matrix if its diagonal elements are equal
- 𝟔
- 𝟎
- 𝟎
- 𝟎
- 𝟔
- 𝟎
- 𝟎
- 𝟎
- 𝟔
- 𝟑
- 𝑿
- 𝟑
- IDENTITY MATRIX:
- A diagonal matrix where all the diagonal elements are identity is known as Identity matrix.
- 𝟏
- 𝟎
- 𝟎
- 𝟎
- 𝟏
- 𝟎
- 𝟎
- 𝟎
- 𝟏
- 𝟑
- 𝑿
- 𝟑
- NULL MATRIX:
- A matrix whose each element is equal to zero is known as a null matrix.
- 0
- 0
- 0
- 1
- 𝑋
- 3
- 0
- 0
- 0
- 𝟎
- 𝟎
- 𝟎
- 𝟎
- 𝟎
- 𝟎
- 𝟎
- 𝟎
- 𝟎
- 𝟑
- 𝑿
- 𝟑

### Slide 7
- Rank
- of
- Matrix
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 6
- Rank of a matrix is defined as the maximum number of linearly independent column vectors in a matrix or the maximum number of linearly independent row vectors in a matrix
- .
- By using elementary transformations to reduce the matrix in a triangular form, the rank of  matrix can be evaluated
- .
- It is denoted by 𝜌

### Slide 8
- Normal Form Of Matrix
- 7
- Example-1
- :
- Find the normal form and hence rank of the matrix
- 𝐴
- =
- 1
- 2
- 2
- 2
- 1
- −2
- 2
- −2
- 1
- Solution
- :
- 1
- 2
- 2
- 2
- 1
- −2
- 2
- −2
- 1
- ~
- 1
- 2
- 2
- 0
- −3
- −6
- 0
- −6
- −3
- 𝑅
- 2
- →
- 𝑅
- 2
- −2
- 𝑅
- 1
- 𝑅
- 3
- →
- 𝑅
- 3
- −2
- 𝑅
- 1
- ~
- 1
- 2
- 2
- 0
- −3
- −6
- 0
- 0
- 9
- 𝑅
- 3
- →
- 𝑅
- 3
- −2
- 𝑅
- 2
- ~
- 1
- 0
- 0
- 0
- −3
- −6
- 0
- −6
- −3
- 𝐶
- 2
- →
- 𝐶
- 2
- −2
- 𝐶
- 1
- 𝐶
- 3
- →
- 𝐶
- 3
- −2
- 𝐶
- 1
- ~
- 1
- 0
- 0
- 0
- −3
- 0
- 0
- 0
- 9
- 𝐶
- 3
- →
- 𝐶
- 3
- −2
- 𝐶
- 2
- ~
- 1
- 0
- 0
- 0
- 1
- 0
- 0
- 0
- 1
- 𝐶
- 2
- →
- −1
- 3
- 𝐶
- 2
- 𝐶
- 3
- →
- 1
- 9
- 𝐶
- 3
- ~
- 𝐼
- 3
- Hence, the normal form of the given matrix is:
- 𝐼
- 3
- and its rank is 3

### Slide 9
- Applications of
- the Matrices
- 1. Computer
- Graphics
- Concepts Used:
- Matrix multiplication, transformation matrices
- Application:
- Rotating, scaling, and translating images or 3D models in games, movies, and simulations.
- Example:
- A transformation matrix can rotate a 2D image around a point using matrix multiplication
- .
- 2
- .
- Machine Learning & Artificial Intelligence
- Concepts Used:
- Matrix multiplication, dot products, identity matrices
- Application:
- Training neural networks, representing datasets, and computing weights in layers.
- Example:
- In a neural network, the input data and weights are often stored as matrices for efficient computation.
- </a:r><a:br><a:rPr lang="en-GB" dirty="0"><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/></a:rPr></a:br><a:r><a:rPr lang="en-GB" b="1" dirty="0"><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/></a:rPr><a:t>3. Economics & Business (Input-Output Models)
- Concepts Used:
- Matrix equations, inverse matrices
- Application:
- Leontief input-output model to study interdependencies in economic sectors.
- Example:
- How much of each product needs to be produced to satisfy certain consumption requirements
- .
- 8

### Slide 10
- Summary of the Lecture
- Studied
- the
- basic concept of matrices along with various types
- .
- 2.
- Learned the
- concept of rank of a
- matrix
- 9

### Slide 11
- Next Lecture
- 10
- Consistency of system of equations
- Eigen values and Vectors
- Cayley Hamilton Theorem

### Slide 12
- Quiz
- 11
- 1.
- If a matrix has all zero elements, its rank is:
- </a:r><a:br><a:rPr lang="en-GB" dirty="0"/></a:br><a:r><a:rPr lang="en-GB" dirty="0"/><a:t>A. 0
- B. 1
- C. Cannot be determined
- D. Equal to the number of rows
- 2
- . The rank of a matrix is:
- </a:r><a:br><a:rPr kumimoji="0" lang="en-US" altLang="en-US" b="0" i="0" u="none" strike="noStrike" cap="none" normalizeH="0" baseline="0" dirty="0" smtClean="0"><a:ln><a:noFill/></a:ln><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:effectLst/><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/></a:rPr></a:br><a:r><a:rPr kumimoji="0" lang="en-US" altLang="en-US" b="0" i="0" u="none" strike="noStrike" cap="none" normalizeH="0" baseline="0" dirty="0" smtClean="0"><a:ln><a:noFill/></a:ln><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:effectLst/><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/></a:rPr><a:t>A. The number of rows
- B. The number of non-zero elements
- C. The number of linearly independent rows or columns
- D. The size of the largest square submatrix

### Slide 13
- Articles
- https
- ://
- www.geeksforgeeks.org/matrices
- https://math.libretexts.org/Bookshelves/Applied_Mathematics/Applied_Finite_Mathematics_%
- 28Sekhon_and_Bloom%29/02%3A_Matrices/2.01%3A_Introduction_to_Matrices
- 12

### Slide 14
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://
- www.coursera.org/learn/matrix-algebra-engineers
- https://
- onlinecourses.nptel.ac.in/noc25_ma14/preview
- https
- ://
- www.coursera.org/learn/matrix-algebra-determinants-and-eigenvectors
- 13

### Slide 15
- Class-Wise
- Feedback
- 14
- https://forms.gle/yc7yfgLaTbYd5D4AA

### Slide 16
- Thank You
- For queries
- Email:
- shivanibansal.maths@cumail.in
- 15


## zero lec
### Slide 1
- UNIVERSITY INSTITUTE OF UIE
- Engineering Foundations
- -
- 1 to 5
- Bachelor of Engineering
- All Branches / SEMESTER-1
- Mathematics-I
- (
- 26SMT-121
- )
- Shivani
- Bansal (E5471)
- CUmail
- -ID : shivanibansal.maths@cumail.in
- Assistant Professor
- Academic Session
- 2026-27
- ODD Semester Jul-Dec
- 2026

### Slide 2
- Vision of University
- “To be globally recognized as a Centre of Excellence for Research, Innovation, Entrepreneurship and disseminating knowledge by providing inspirational learning to produce professional leaders for serving the society.”
- 1

### Slide 3
- Mission of University
- M1 :
- Providing world class infrastructure, renowned academicians and ideal environment for Research, Innovation, Consultancy and Entrepreneurship relevant to the society.
- M2 :
- Offering programs & courses in consonance with National policies for nation building and meeting global challenges.
- 2

### Slide 4
- Mission of University
- M3
- :	Designing Curriculum to match International standards, needs of Industry, civil 	society and for inculcation of traits of Creative Thinking and Critical Analysis as well as Human and Ethical values.
- M4
- :	Ensuring students delight by meeting their aspirations through blended learning, corporate mentoring, professional grooming, flexible curriculum and healthy atmosphere based on co-curricular and extra-curricular activities.
- 3

### Slide 5
- Mission of University
- M5
- :	Creating a scientific, transparent and objective examination/evaluation system to ensure an ideal certification.
- M6
- :	Establishing strategic relationships with leading National and International corporates and universities for academic as well as research collaborations.
- 4

### Slide 6
- Mission of University
- M7:
- Contributing for creation of healthy, vibrant and sustainable society by involving in Institutional Social Responsibility (ISR) activities like rural development, welfare of 	senior citizens, women empowerment, community service, health and hygiene awareness and environmental protection.
- 5

### Slide 7
- Vision of Department
- To be recognized as a leading
- UIE
- department through effective teaching practices and excellence in research and innovation for creating competent professionals with ethics, values and entrepreneurial attitude to deliver service to society and to meet the current industry standards at the global level.
- 6

### Slide 8
- Mission of Department
- M1
- :	To provide practical knowledge using state-of-the-art technological support for the experiential learning of our students.
- M2
- :	To provide industry recommended curriculum and transparent assessment for quality learning experiences.
- M3
- :	To create global linkages for interdisciplinary collaborative learning and research.
- 7

### Slide 9
- Program Educational Objectives (PEOs)
- PEO 1:
- To produce
- Computer science
- graduate engineers with an ability to comprehend, understand and analyze real life problems for providing sustainable solutions in the light of disruptive technologies.
- PEO 2:
- To inculcate life-long learning skills in graduates preparing them for work in changing environments and multidisciplinary teams in order to enhance their capability being globally employable.
- </a:r><a:br><a:rPr lang="en-US" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:rPr></a:br><a:endParaRPr lang="en-US" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:endParaRPr></a:p></p:txBody></p:sp><p:sp><p:nvSpPr><p:cNvPr id="7" name="TextBox 6"/><p:cNvSpPr txBox="1"/><p:nvPr/></p:nvSpPr><p:spPr><a:xfrm><a:off x="8709003" y="85987"/><a:ext cx="284052" cy="307777"/></a:xfrm><a:prstGeom prst="rect"><a:avLst/></a:prstGeom><a:noFill/></p:spPr><p:txBody><a:bodyPr wrap="none" rtlCol="0"><a:spAutoFit/></a:bodyPr><a:lstStyle/><a:p><a:r><a:rPr lang="en-IN" dirty="0" smtClean="0"/><a:t>8

### Slide 10
- Program Outcome (POs)
- PO1:
- Engineering Knowledge: Apply the knowledge of mathematics, science, engineering fundamentals and an engineering specialization to the solution of complex engineering
- problems
- PO2:
- Problem Analysis: Identify, formulate, review research literature and
- analyze
- complex engineering problems reaching substantiated conclusions using first principles mathematics, natural sciences and engineering
- sciences
- </a:r><a:br><a:rPr lang="pl-PL" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:rPr></a:br><a:endParaRPr lang="pl-PL" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:endParaRPr></a:p></p:txBody></p:sp><p:sp><p:nvSpPr><p:cNvPr id="7" name="TextBox 6"/><p:cNvSpPr txBox="1"/><p:nvPr/></p:nvSpPr><p:spPr><a:xfrm><a:off x="8709003" y="85987"/><a:ext cx="284052" cy="307777"/></a:xfrm><a:prstGeom prst="rect"><a:avLst/></a:prstGeom><a:noFill/></p:spPr><p:txBody><a:bodyPr wrap="none" rtlCol="0"><a:spAutoFit/></a:bodyPr><a:lstStyle/><a:p><a:r><a:rPr lang="en-IN" dirty="0" smtClean="0"/><a:t>9

### Slide 11
- Program Outcome (POs)
- PO
- 3
- :
- Design/Development of Solutions: Design solutions for complex engineering problems and design system components or processes that meet specified needs with appropriate consideration for public health and safety, and the cultural, societal, and environmental considerations
- .
- PO
- 4
- :
- Conduct investigations of Complex Problems: Use research-based knowledge and research methods including design of experiments, analysis and interpretation of data and synthesis of the information to provide valid conclusion
- </a:r><a:br><a:rPr lang="pl-PL" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:rPr></a:br><a:endParaRPr lang="pl-PL" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:endParaRPr></a:p></p:txBody></p:sp><p:sp><p:nvSpPr><p:cNvPr id="7" name="TextBox 6"/><p:cNvSpPr txBox="1"/><p:nvPr/></p:nvSpPr><p:spPr><a:xfrm><a:off x="8709003" y="85987"/><a:ext cx="383438" cy="307777"/></a:xfrm><a:prstGeom prst="rect"><a:avLst/></a:prstGeom><a:noFill/></p:spPr><p:txBody><a:bodyPr wrap="none" rtlCol="0"><a:spAutoFit/></a:bodyPr><a:lstStyle/><a:p><a:r><a:rPr lang="en-IN" dirty="0" smtClean="0"/><a:t>10

### Slide 12
- Program Outcome (POs)
- PO
- 5
- :
- Modern Tool Usage: Create, select, and apply appropriate techniques, resources and modern engineering and IT tools including prediction and modelling to complex engineering activities with an understanding of the
- limitations.
- PO
- 6
- :
- The Engineer and Society: Apply reasoning informed by the contextual knowledge to assess societal, health, safety, legal and cultural issues and the consequent responsibilities relevant to the professional engineering
- practice.
- 11

### Slide 13
- Program Outcome (POs)
- PO
- 7
- :
- Environment and Sustainability: Understand the impact of the professional engineering solutions in societal and environmental contexts, and demonstrate the knowledge of, and need for sustainable development
- PO
- 8
- :
- Ethics: Apply ethical principles and commit to professional ethics and responsibilities and norms of the engineering
- practice
- 12

### Slide 14
- Program Outcome (POs)
- PO
- 9
- :
- Individual and Teamwork: Function effectively as an individual, and as a member or leader in diverse teams, and in multidisciplinary
- settings
- PO
- 10
- :
- Communication: Communicate effectively on complex engineering activities with the engineering community and with society at large, such as, being able to comprehend and write effective reports and design documentation, make effective presentations, and give and receive clear instructions.
- </a:r><a:br><a:rPr lang="pl-PL" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:rPr></a:br><a:endParaRPr lang="pl-PL" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:endParaRPr></a:p></p:txBody></p:sp><p:sp><p:nvSpPr><p:cNvPr id="7" name="TextBox 6"/><p:cNvSpPr txBox="1"/><p:nvPr/></p:nvSpPr><p:spPr><a:xfrm><a:off x="8709003" y="85987"/><a:ext cx="383438" cy="307777"/></a:xfrm><a:prstGeom prst="rect"><a:avLst/></a:prstGeom><a:noFill/></p:spPr><p:txBody><a:bodyPr wrap="none" rtlCol="0"><a:spAutoFit/></a:bodyPr><a:lstStyle/><a:p><a:r><a:rPr lang="en-IN" dirty="0" smtClean="0"/><a:t>13

### Slide 15
- Program Outcome (POs)
- PO
- 11
- :
- Project Management and Finance: Demonstrate knowledge and understanding of the engineering and management principles and apply these to one's own work, as a member and leader in a team, to manage projects and in multidisciplinary
- environments
- PO
- 1
- 2
- :
- Life-long Learning: Recognize the need for, and have the preparation and ability to engage in independent and life-long learning in the broadest context to technological change.
- </a:r><a:br><a:rPr lang="pl-PL" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:rPr></a:br><a:endParaRPr lang="pl-PL" sz="3000" b="1" i="0" u="none" strike="noStrike" cap="none" dirty="0"><a:solidFill><a:schemeClr val="bg2"/></a:solidFill><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:ea typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:sym typeface="Arial"/></a:endParaRPr></a:p></p:txBody></p:sp><p:sp><p:nvSpPr><p:cNvPr id="7" name="TextBox 6"/><p:cNvSpPr txBox="1"/><p:nvPr/></p:nvSpPr><p:spPr><a:xfrm><a:off x="8709003" y="85987"/><a:ext cx="383438" cy="307777"/></a:xfrm><a:prstGeom prst="rect"><a:avLst/></a:prstGeom><a:noFill/></p:spPr><p:txBody><a:bodyPr wrap="none" rtlCol="0"><a:spAutoFit/></a:bodyPr><a:lstStyle/><a:p><a:r><a:rPr lang="en-IN" dirty="0" smtClean="0"/><a:t>14

### Slide 16
- Program Outcome (POs)
- PO
- 13
- :
- Application of Mathematics and Science: Use mathematical and scientific concepts to model,
- analyze
- , and optimize electronic systems
- PO
- 1
- 4
- :
- Teamwork and Communication Skills: Work effectively in teams to design and implement electronic projects, and communicate technical ideas clearly through presentations and reports
- .
- PO15:
- Professional Ethics and Responsibility: Recognize the ethical considerations and professional responsibilities associated with electronics engineering practices
- .
- 15

### Slide 17
- Program Outcome (POs)
- PO
- 16
- :
- Throughout life Learning: Demonstrate the ability to adapt and learn new technologies and concepts in the evolving field of electronics engineering
- .
- PO
- 1
- 7
- :
- Sustainability and Societal Impact: Understand the societal and environmental impact of electronic technologies and aim for sustainable practices in engineering solutions
- .
- 16

### Slide 18
- Program Specific Outcome (PSOs)
- A Graduate of
- Computer Science Engineering
- Program will be able
- :
- PSO1:
- Exhibit
- attitude for continuous learning and deliver efficient solutions for emerging challenges in the computation domain.
- PSO2:
- Apply standard software engineering principles to develop viable solutions for Information Technology Enabled Services (ITES).
- 17

### Slide 19
- 18

### Slide 20
- 19

### Slide 21
- Course Information
- Prerequisite:
- L
- T   P  Cr
- Mathematics
- upto
- 10+2 level
- 3
- 2
- 0
- 5
- Objectives
- The objective of this course is to familiarize the prospective engineers with techniques in Matrices, Infinite Series and differential equations
- .
- It aims to equip the students with standard concepts and tools at an intermediate to advanced level that will serve them well towards solving more advanced level of mathematics and applications that they would find useful in their respective disciplines.
- 20

### Slide 22
- Course Outcomes
- 21
- CO1
- Define the fundamentals of
- matrices,
- Infinite
- Series
- and differential equations
- .
- CO2
- Identify and distinguish the types of matrices,
- Infinite
- Series
- and  differential equations
- .
- CO3
- Understand the various concepts and properties of matrices
- ,
- Infinite
- Series
- ,
- and differential equations used in solving mathematical problems.

### Slide 23
- Course Outcomes
- 22
- CO4
- Apply the principles of matrices
- , Infinite
- Series
- and
- differential equations to address engineering problems with real life applications
- .
- CO5
- Apply appropriate method to determine the solution of some advanced level problems involving matrices,
- Infinite
- Series
- and
- differential equations.

### Slide 24
- Importance/Applications
- of
- Subject:
- Matrices
- 23
- Field
- Application of Matrices
- Electrical Engineering
- Used in circuit analysis, especially in nodal and mesh
- analysis.
- Mechanical Engineering
- Applied in structural analysis (e.g., stiffness matrices in FEM), dynamics (mass, damping, stiffness
- matrices)
- Civil Engineering
- Structural load analysis, finite element methods (FEM
- ).
- Computer Engineering
- Image processing (pixel manipulation), 3D transformations in graphics, neural networks
- and encryption algorithms.
- Control Systems
- State-space representation of dynamic systems, transfer function analysis, and stability assessment.
- Telecommunication
- Signal processing, error detection and correction, coding theory, and information theory.

### Slide 25
- Syllabus (Theory)
- Unit-1
- Matrices and its
- Applications
- Contact
- Hours:25
- Basics
- of Matrices
- Introduction to matrices, Types of matrices, orthogonal and unitary matrices, Rank of matrices, Elementary transformations, Reduction to echelon form
- .
- Applications of Matrices
- Consistency and solution of system of linear equations using matrices, Eigen values & Eigen Vectors, Linear dependence and independence of vectors, Cayley Hamilton Theorem (without proof), Inverse using Cayley Hamilton Theorem.
- Self Study
- Topics
- Diagonalization of Matrices, Modal matrix.
- 24

### Slide 26
- MST Model QP
- 25

### Slide 27
- E
- ST Model QP
- 26

### Slide 28
- E
- ST Model QP
- 27

### Slide 29
- Text
- Books
- T1:
- Advanced
- Engineering
- Mathematics by E
- .
- Kreyszig
- , 10th Edition,
- John Wiley, New
- Delhi, 2011.
- T2:
- Advanced Engineering
- Mathematics by R.K
- . Jain and S.R.K.
- Iyengar
- ,
- 3rd Edition
- Narosa
- Publishing
- House
- , New
- Delhi, 2004.
- T3:
- Higher Engineering Mathematics
- by H.K
- .
- Dass
- , 3rd
- revised
- edition,
- S Chand
- Publishers, 2014
- .
- 28

### Slide 30
- R
- eference Books
- R1: A
- textbook of Engineering
- Mathematics by
- N.P. Bali and Manish
- Goyal,
- Ninth edition
- Laxmi
- Publications
- 2010.
- R2:
- Advanced Engineering
- Mathematics by B.V
- .
- Ramana
- ,
- 1st
- Edition,
- McGraw Hill, New
- Delhi,
- 2006
- R3: Calculus
- and Analytic Geometry
- by B
- . Thomas and R.L.
- Finney,
- 11th
- Edition,
- Pearson
- Education,
- 2004
- 29

### Slide 31
- E-Learning links
- NPTEL :: Mathematics - Matrix
- Theory
- NPTEL :: Mathematics -
- NOC:Linear
- Algebra
- NPTEL :: Mathematics -
- NOC:Differential
- equations for engineers
- 30

### Slide 32
- Content Beyond Syllabus
- Diagonalization of Matrices, Modal matrix
- .
- Inner product spaces, Gram-Schmidt
- orthogonalization
- .
- Clairaut’s
- form, Equations solvable for p, simultaneous linear equation with constant coefficients.
- 31

### Slide 33
- Assessment Model
- 32
- Evaluation Type
- Evaluation Instrument
- Marks
- Duration/Frequency
- Final Weightage
- Total Marks
- Formative Assessment
- Assignment
- 4 per Assignment
- 1 per unit
- 12
- 100
- Formative Assessment
- Quiz
- 3 per quiz
- 2 per semester
- 6
- Interim Summative Assessments
- MST-1
- 20
- 1 Hour
- 10
- MST-2
- 20
- 1 Hour
- 10
- Formative Assessment
- Case study
- 10
- 1 per semester
- 10
- Formative Assessment
- Attendance
- NA
- NA
- 2
- Semester End Examination
- End Term Exam
- 50
- 3 Hours
- 50

### Slide 34
- Thank You
- 33


---


================================================================================


# Chapter 1.2 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Cayley Hamilton Theorem 1.2.7
# Cayley Hamilton Theorem 1.2.7

## The topic is associated with the following course outcomes:

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

CO5

Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series and differential equations.

##

## The Cayley-Hamilton Theorem is a powerful result in linear algebra with several practical applications in mathematics, engineering, physics, and computer science.

## 1. Computing Higher Powers of Matrices

Use: You can express

AnA^n

in terms of lower powers of

AA

.

Why it matters: Saves computation and storage, especially in iterative methods or simulations.

## 2. Finding the Inverse of a Matrix (for non-singular matrices)

Use: Use the characteristic polynomial to express

A−1A^{-1}

as a linear combination of

A,A2,…

Example:

If

A2−5A+6I=0A^2 - 5A + 6I = 0

, rearrange:

A−1=16(A−I)A^{-1} = \frac{1}{6}(A - I)

## 3. Simplifying Matrix Functions (e.g.,

eA,sin⁡Ae^A, \sin A

## )

Use: Reduce the infinite series of functions like

eAe^A

to a finite one using the characteristic polynomial.

Why it matters: Essential in solving linear differential equations and modeling dynamic systems.

##

## 4. Control Theory: State Space Analysis

Use: Used in computing the transition matrix and checking system controllability/observability.

Why it matters: Helps in designing controllers and analyzing dynamic behavior of systems.

## 5. Computational Optimization

Use: In numerical algorithms to avoid repeated multiplications for matrix exponentiation.

Why it matters: Reduces time complexity in simulations and computer graphics.

## 6. Engineering (Signal Processing, Vibrations)

Use: Analyzing systems described by matrix equations—helps in characterizing resonance and system response.

Why it matters: Essential for modeling real-world systems.

##

##

## Extra Study Material Links:

Cayley Hamilton Theorem - Statement, Formula, Proof, Examples

Cayley Hamilton Theorem | GeeksforGeeks

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Consistency of System of Equations 1.2.1, 1.2.2
# Consistency of System of Equations 1.2.1, 1.2.2

## The topic is associated with the following course outcomes:

CO3

Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

##                                                                Consistency of Linear equations

A system of m linear equations in n variables will look like:

a11 x1+a12 x2+ …………+a1n xn= b1

a21 x1+a22 x2+ …………+a2n xn= b2

am1 x1+am2 x2+ …………+amn xn= bm

- Matrix Form of the Linear Equations: The following is the representation of the linear equations in matrix form:

a11  a1n  ⋱  am1  amn x1  xn =b1  bm

i.e.  AX=B

The system of equations is of two types:

- Homogeneous Equations: Where the column matrix B is all zero

- Non-Homogeneous equations: Where the column matrix B has non-zero elements.

A system of linear equations is said to be consistent if it has a solution.

If a system of linear equations has no solution then it is said to be inconsistent.

For a consistent system, there are two types of solutions:

- Unique solution

- Infinite Solution

For a system of linear equations: i.e.  AX=B, in order to check the consistency, a new matrix named as AUGMENTED matrix is created as follows:

A⋮B

This is done by clubbing the coefficient matrix A with the matrix B

By applying elementary transformations, the rank of the augmented matrix and the matrix A is obtained.

If A⋮B=ρ(A), then the system is said to be consistent i.e. it has a solution.

If A⋮B≠ρ(A), then the system is said to be inconsistent i.e. it has no solution

## System of non-homogeneous linear equations AX = B

1.    If P [A: B] ≠P(A), No solution.

2.    If P [A: B] = P(A) = the number of unknown variables, unique solution.

3.    If P [A: B] = P(A) ≠ number of unknown, infinite number of solutions.

Here P [A: B] is rank of gauss elimination representation of AX = B.

The consistency of a system of equations whether a system has at least one solution has many practical applications in science, engineering, economics, computer science, and more. Here are key applications across various domains:

## 🔧 1. Engineering and Physics

Structural Analysis: Determining forces in trusses and bridges relies on consistent systems. If the system is inconsistent, it might indicate structural instability.

Electric Circuits: Kirchhoff’s laws result in systems of linear equations; a consistent system means current and voltage distributions are physically possible.

Mechanics: Ensuring equilibrium of forces and torques leads to linear systems—consistency ensures that the mechanical system can be in balance.

## 💻 2. Computer Science and Algorithms

Computer Graphics: Solving for transformations (e.g., scaling, rotation) often involves linear systems. A consistent system ensures valid transformations exist.

Machine Learning: Linear regression fits a line through data by solving a system. Consistency implies that a solution exists, even if approximate.

Cryptography: Some ciphers involve solving linear systems over finite fields. Inconsistency can signal tampering or errors.

## 📈 3. Economics and Finance

Input-Output Models: Leontief’s economic models describe how outputs from one industry are inputs to another. Consistency ensures supply meets demand.

Portfolio Optimization: In finance, systems of equations are used to find asset weights. A consistent system implies a feasible investment strategy.

## 🧬 4. Biology and Chemistry

Reaction Balancing: Chemical equations are modeled as linear systems. Consistency means the reaction can be balanced under conservation laws.

Population Modeling: Linear models describing population dynamics need to be consistent to ensure predictions make biological sense.

## 🏗️ 5. Operations Research

Linear Programming: Feasibility of constraints (a consistent system) determines if a solution exists for optimizing production, logistics, etc.

Network Flows: Flow constraints in supply chains or transportation networks form linear systems—consistency ensures demand and supply can be matched.

##

##

## Extra Study Material Links:

Consistent and Inconsistent Systems of Linear Equations | GeeksforGeeks

NPTEL :: Mathematics - NOC:Matrix Analysis with Applications

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Eigen Values 1.2.5
# Eigen Values 1.2.5

## The topic is associated with the following course outcomes:

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

CO5

Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series and differential equations.

##                                                      Eigen Values

The eigenvalues of matrix are scalars by which some vectors (eigenvectors) change when the matrix (transformation) is applied to it. In other words, if A is a square matrix of order n x n and X is a non-zero column vector of order n x 1 such that

AX = λX

Here, we can see that AX is parallel to X. So, X is an eigen vector.

## Method to find eigen vectors and eigen values of any square matrix A

We know that,

AX = λX

=> AX – λX = 0

=> (A – λI) X = 0 …..(1)

Above condition will be true only if (A – λI) is singular. That means,

|A – λI| = 0 …..(2)

(2) is known as characteristic equation of the matrix.

The roots of the characteristic equation are the eigen values of the matrix A.

Now, to find the eigen vectors, we simply put each eigen value into (1) and solve it by Gaussian elimination, that is, convert the augmented matrix (A – λI) = 0 to row echelon form and solve the linear system of equations thus obtained.

## Some important properties of eigen values

·        Eigen values of real symmetric and hermitian matrices are real

·        Eigen values of real skew symmetric and skew hermitian matrices are either pure imaginary or zero

·        Eigen values of unitary and orthogonal matrices are of unit modulus |λ| = 1

·        If λ1, ,λ2…….λn are the eigen values of A, then kλ1, kλ2…….kλn are eigen values of kA

·        If λ1, λ2…….λn are the eigen values of A, then 1/λ1, 1/λ2…….1/λn are eigen values of A-1

·        If λ1, λ2…….λn are the eigen values of A, then λ1k, λ2k…….λnk are eigen values of Ak

·        Eigen values of A = Eigen Values of AT (Transpose)

·        Sum of Eigen Values = Trace of A (Sum of diagonal elements of A)

·        Product of Eigen Values = |A|

·        Maximum number of distinct eigen values of A = Size of A

·        If A and B are two matrices of same order then, Eigen values of AB = Eigen values of BA

##

## Eigenvalues and eigenvectors have a wide range of applications across various fields, from mathematics and physics to engineering, computer science, and even finance. Here are some of the most important and practical applications of eigenvalues of matrices:

## 🔬 1. Stability Analysis in Systems & Control Theory

Application: In dynamic systems, eigenvalues of the system matrix determine the stability of equilibrium points.

Example: If all eigenvalues of a system’s Jacobian matrix have negative real parts, the system is stable.

## ⚙️ 2. Vibrations and Modal Analysis

Application: In mechanical and structural engineering, eigenvalues are used to find natural frequencies of structures.

Example: Analyzing how bridges, buildings, or cars vibrate under stress or movement.

##

## 🧮 3. Quantum Mechanics

Application: The Schrödinger equation uses eigenvalues to determine allowed energy levels of quantum systems.

Example: The eigenvalues of the Hamiltonian matrix represent energy levels of atoms or molecules.

## 🔁 4. Markov Chains & Google's PageRank

Application: The long-term behavior of Markov processes is determined by the dominant eigenvalue of the transition matrix.

Example: Google uses this concept in the PageRank algorithm to rank web pages.

## 🔌 5. Electrical Circuits & Signal Processing

Application: Eigenvalues help analyze RLC circuits and determine system responses.

Example: Finding resonance frequencies in signal filters.

## 🧠 6. Neural Networks and Deep Learning

Application: Eigenvalues are used to analyze the Hessian matrix in optimization problems and to detect sharp or flat minima.

Example: Understanding generalization in deep learning models.

## 📐 7. Image Compression & Face Recognition

Application: Techniques like Eigenfaces use eigenvalues to identify and compress significant features in facial images.

Example: Reducing storage and improving facial recognition accuracy.

## 🚀 8. Aerospace and Robotics

Application: Eigenvalues are used in analyzing flight dynamics and robot stability.

Example: Determining if an aircraft or robot will return to stable flight or motion after a disturbance.

##

## Extra Study Material Links:

## Eigenvalues and Eigenvectors | GeeksforGeeks

NPTEL :: Mathematics - NOC:Matrix Analysis with Applications

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Eigen Vectors 1.2.6
# Eigen Vectors 1.2.6

## The topic is associated with the following course outcomes:

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

CO5

Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series and differential equations.

##

##

## To find eigenvectors of a matrix, you need to follow a few steps after finding its eigenvalues. Here’s a step-by-step guide:

## 🧮 Step-by-Step Guide

Given: A square matrix A

##

## Step 1: Find Eigenvalues

## Solve the characteristic equation:

det(A−λI)=0

##

λ

##  = eigenvalues

I

##  = identity matrix of same size as A.

This gives you the eigenvalues

λ1,λ2,…\lambda_1, \lambda_2, \ldots

## Step 2: Solve for Eigenvectors

For each eigenvalue

λ\lambda

, solve:

(A−λI)x⃗=0(A - \lambda I)\vec{x} = 0

## This is a homogeneous system of linear equations. The non-zero solutions x

## ⃗ are the eigenvectors corresponding to eigenvalue λ.

##  Eigen vector Applications

There are different applications of eigenvectors in real life. Some of the important ones are provided below:

1) In Mathematics, eigenvector decomposition is widely used in order to solve linear equations of the first order, in ranking matrices, in differential calculus, etc.

2) Eigenvectors are used in Physics in the simple mode of oscillation.

3) This concept is widely used in quantum mechanics.

4) Eigenvectors are widely applicable in almost all branches of engineering.

5) Eigenvalues can be used to calculate the theoretical limit of the transmission of information through a medium of communication like a telephone line or through the air. It is done by finding the eigenvalues and eigenvectors of the channel that is used for communication and then water-filling on the eigenvalues.

6) Eigenvalue is the natural frequency that is the smallest magnitude of a system that builds the bridge. The stability of the construction can be monitored by using this.

7) The concept of eigenvalues is used in the construction of a car stereo system. It helps in the reproduction of the vibration of the car due to the music.

8) It is used in decoupling three-phase systems along the symmetrical component transformation.

9) It helps in the reduction of a linear operation to separate simpler problems.

10) Many oil companies generally use eigenvalue analysis to survey land for oil.

11) It is used to explain natural occurrences.

12) The linear mapping eigenvalues measure the distortion induced by the transformation, and eigenvectors explain the orientation of the distortion.

## Extra Study Material Links:

Eigenvalues and Eigenvectors | GeeksforGeeks

NPTEL :: Mathematics - NOC:Matrix Analysis with Applications

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Homogeneous System of equations 1.2.3
# Homogeneous System of equations 1.2.3

## The topic is associated with the following course outcomes:

CO3

Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

##

## System of homogeneous linear equations AX = 0.

1.    X = 0. is always a solution; means all the unknowns has same value as zero. (This is also called trivial solution)

2.    If P(A) = number of unknowns, unique solution.

3.    If P(A) < number of unknowns, infinite number of solutions.

##

## The consistency of a system of equations whether a system has at least one solution has many practical applications in science, engineering, economics, computer science, and more. Here are key applications across various domains:

## 🔧 1. Engineering and Physics

Structural Analysis: Determining forces in trusses and bridges relies on consistent systems. If the system is inconsistent, it might indicate structural instability.

Electric Circuits: Kirchhoff’s laws result in systems of linear equations; a consistent system means current and voltage distributions are physically possible.

Mechanics: Ensuring equilibrium of forces and torques leads to linear systems—consistency ensures that the mechanical system can be in balance.

## 💻 2. Computer Science and Algorithms

Computer Graphics: Solving for transformations (e.g., scaling, rotation) often involves linear systems. A consistent system ensures valid transformations exist.

Machine Learning: Linear regression fits a line through data by solving a system. Consistency implies that a solution exists, even if approximate.

Cryptography: Some ciphers involve solving linear systems over finite fields. Inconsistency can signal tampering or errors.

## 📈 3. Economics and Finance

Input-Output Models: Leontief’s economic models describe how outputs from one industry are inputs to another. Consistency ensures supply meets demand.

Portfolio Optimization: In finance, systems of equations are used to find asset weights. A consistent system implies a feasible investment strategy.

## 🧬 4. Biology and Chemistry

Reaction Balancing: Chemical equations are modeled as linear systems. Consistency means the reaction can be balanced under conservation laws.

Population Modeling: Linear models describing population dynamics need to be consistent to ensure predictions make biological sense.

## 🏗️ 5. Operations Research

Linear Programming: Feasibility of constraints (a consistent system) determines if a solution exists for optimizing production, logistics, etc.

Network Flows: Flow constraints in supply chains or transportation networks form linear systems—consistency ensures demand and supply can be matched.

##

## Extra Study Material Links:

A Homogeneous System of Linear Equations is Always Consistent. | GeeksforGeeks

NPTEL :: Mathematics - NOC:Matrix Analysis with Applications

Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Linear dependence and Linear independence of vectors 1.2.4
# Linear dependence and Linear independence of vectors 1.2.4

## The topic is associated with the following course outcomes:

CO3

Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

## Linear dependence and Linear independence of vectors

Linear Dependence:

A set of vectors X1 ,X2 ….Xr is said to be linearly dependent if there exist r scalars k1 ,k2 …..kr such that: k1 X1 + k2X2 +……..kr Xr = 0.

Linear Independence:

A set of vectors X1 ,X2….Xr is said to be linearly independent if for all r scalars k1,k2 …..krsuch that k1X1+ k2 X2+……..krXr = 0, then k1 = k2 =……. = kr = 0.

How to determine linear dependency and independency?

Let X1, X2 ….Xr be the given vectors. Construct a matrix with the given vectors as its rows.

1.    If the rank of the matrix of the given vectors is less than the number of vectors, then the vectors are linearly dependent.

2.    If the rank of the matrix of the given vectors is equal to the number of vectors, then the vectors are linearly independent.

##

## The concepts of linear dependence and linear independence of vectors are fundamental in linear algebra, and they play a crucial role in many real-world applications across various fields. Here's a breakdown of their applications:

## ✅ 1. Solving Systems of Linear Equations

Use: Determining whether a system has a unique solution, no solution, or infinitely many.

Why it matters: If the columns of the coefficient matrix are linearly independent, the system has a unique solution.

## ✅ 2. Computer Graphics & 3D Modeling

Use: Ensuring coordinate systems (e.g., camera basis, transformation matrices) are valid.

Why it matters: You need linearly independent basis vectors to define rotation and perspective transformations correctly.

## ✅ 3. Machine Learning & Feature Selection

Use: Identifying and removing redundant features (linear dependence among features).

Why it matters: Linearly dependent features don’t add new information and can harm model performance (e.g., multicollinearity).

## ✅ 4. Cryptography

Use: Matrix-based encryption methods (e.g., Hill cipher) require the key matrix to be invertible.

Why it matters: A matrix is invertible only if its rows (or columns) are linearly independent.

## ✅ 5. Control Systems and Robotics

Use: Analyzing the controllability and observability of a system.

Why it matters: If the system's controllability matrix has linearly independent rows, the system is controllable (can be guided to any state).

##

## Extra Study Material Links:

2.5: Linear Independence - Mathematics LibreTexts

NPTEL :: Mathematics - NOC:Matrix Computation and its applications

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


## 🖥️ PRESENTATION SLIDES


# Chapter 1.2 - All Lecture Slides Text


## ch-2
### Slide 1
- UNIVERSITY INSTITUTE OF
- UIE
- Engineering Foundations-
- 1
- to 5
- Bachelor of Engineering
- All Branches
- / SEMESTER-1
- Mathematics-I
- (
- 26SMT-121
- )
- Unit
- No.
- 1
- Chapter No. 2
- Topic
- :
- Applications of Matrices
- Shivani
- Bansal and E5471                                                       Assistant Professor
- Academic Session
- 2026-27
- ODD Semester
- Jul-Dec
- 2026

### Slide 2
- Learning Objectives
- To
- understand
- the Consistency of system of equations.
- 2. To Learn
- the concept of
- Eigen values and vectors of a matrix.
- 3. To study Cayley Hamilton Theorem.
- 1

### Slide 3
- Applications
- of Matrices
- Topic 1
- .
- Consistency of system of
- equations
- Topic
- 2
- .
- Eigen values and vectors of a
- matrix
- Topic 3
- .
- Cayley Hamilton Theorem
- 2

### Slide 4
- Consistency &
- Inconsistent
- system
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 3
- A system of linear equations may or may not have a solution.
- A system of linear equations is said to be
- consistent
- if it has a solution.
- If a system of linear equations has no solution then it is said to be
- inconsistent.
- For a consistent system, there are two types of solutions
- :
- Unique
- solution
- Infinite Solution

### Slide 5
- Condition for consistency
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 4

### Slide 6
- Eigen values and vectors
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 5
- An
- eigenvector
- of a square matrix
- A
- is a
- non-zero vector
- v
- such that when the matrix acts on
- v
- , the output is just a
- scaled version
- of
- v
- itself
- .
- Av⃗=
- λ
- v
- ⃗
- A:
- a square
- matrix
- v
- ⃗:
- the eigenvector (non-zero vector
- )
- λ:
- the
- eigenvalue
- , a scalar

### Slide 7
- Cayley Hamilton Theorem
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 6
- Statement:
- Every square matrix satisfies its own characteristic equation
- .
- Let A = [
- a
- ij
- ]
- n×n
- be a square matrix then,
- 𝐴
- =
- 𝑎
- 11
- 𝑎
- 12
- ...
- 𝑎
- 1
- 𝑛
- 𝑎
- 21
- 𝑎
- 22
- ...
- 𝑎
- 2
- 𝑛
- ....
- ....
- ....
- ....
- 𝑎
- 𝑛
- 1
- 𝑎
- 𝑛
- 2
- ...
- 𝑎
- 𝑛𝑛
- 𝑛
- ×
- 𝑛

### Slide 8
- Applications of
- the Matrices
- 1. Computer
- Graphics
- Concepts Used:
- Matrix multiplication, transformation matrices
- Application:
- Rotating, scaling, and translating images or 3D models in games, movies, and simulations.
- Example:
- A transformation matrix can rotate a 2D image around a point using matrix multiplication
- .
- 2
- .
- Machine Learning & Artificial Intelligence
- Concepts Used:
- Matrix multiplication, dot products, identity matrices
- Application:
- Training neural networks, representing datasets, and computing weights in layers.
- Example:
- In a neural network, the input data and weights are often stored as matrices for efficient computation.
- </a:r><a:br><a:rPr lang="en-GB" dirty="0"><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/></a:rPr></a:br><a:r><a:rPr lang="en-GB" b="1" dirty="0"><a:latin typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/><a:cs typeface="Calibri" panose="020F0502020204030204" pitchFamily="34" charset="0"/></a:rPr><a:t>3. Economics & Business (Input-Output Models)
- Concepts Used:
- Matrix equations, inverse matrices
- Application:
- Leontief input-output model to study interdependencies in economic sectors.
- Example:
- How much of each product needs to be produced to satisfy certain consumption requirements
- .
- 7

### Slide 9
- Summary of the Lecture
- Studied
- the
- basic concept of matrices along with various types
- .
- 2.
- Learned the
- concept of rank of a
- matrix
- 8

### Slide 10
- Quiz
- 9
- 1.
- For a matrix
- A,
- the Cayley-Hamilton theorem can be used to find:
- A. Determinant of
- A
- B. Inverse of
- A
- C. Rank of
- A
- D. None of the above
- 2
- .
- The eigenvalues of a triangular matrix are:
- A. All zero
- B. The entries on the main diagonal
- C. The determinant of the matrix
- D. The sum of each row

### Slide 11
- Articles
- https://www.geeksforgeeks.org/applications-of-eigenvalues-and-eigenvectors
- /
- https
- ://
- math.libretexts.org/Courses/Irvine_Valley_College/Math_26%3A_Introduction_to_Linear_Algebra/03%3A_Eigenvalues_and_Eigenvectors
- 10

### Slide 12
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://
- www.coursera.org/learn/matrix-algebra-engineers
- https://
- onlinecourses.nptel.ac.in/noc25_ma14/preview
- https
- ://
- www.coursera.org/learn/matrix-algebra-determinants-and-eigenvectors
- 11

### Slide 13
- Class-Wise
- Feedback
- 12
- https://forms.gle/yc7yfgLaTbYd5D4AA

### Slide 14
- Thank You
- For queries
- Email:
- shivanibansal.maths@cumail.in
- 13


---


================================================================================


# Chapter 2.1 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Cauchy's Root test 2.1.6
# Cauchy's Root test 2.1.6

## The topic is associated with the following course outcomes:

##

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

## CO4

## Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

##

##

##

##

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and

signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

9.6: Ratio and Root Tests - Mathematics LibreTexts

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Comparision test 2.1.4
# Comparision test 2.1.4

## The topic is associated with the following course outcomes:

## CO2

## Identify and distinguish the types of matrices, infinite series and  differential equations.

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

##

##

##

##

##

##

##

##

## Comparison test

##

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and

signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

9.4: Comparison Tests - Mathematics LibreTexts

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Infinite series 2.1.3
# Infinite series 2.1.3

## The topic is associated with the following course outcomes:

## CO2

## Identify and distinguish the types of matrices, infinite series and  differential equations.

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

##

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and

signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

9.2: Infinite Series - Mathematics LibreTexts

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Introduction to Sequences 2.1.1
# Introduction to Sequences 2.1.1

##

## The topic is associated with the following course outcomes:

## CO1

## Define the fundamentals of matrices, infinite series and differential equations.

## CO2

## Identify and distinguish the types of matrices, infinite series and differential equations.

## Applications of Sequences

## Some real-life applications of sequences are:

## Population Growth – The increase in population over time often follows a sequence pattern.

## Bank Interest and Investments – Compound interest calculations use geometric sequences to determine future value of money.

## Computer Algorithms – Sequences are used in programming, data structures, and analysis of algorithms.

## Signal Processing – Digital signals in audio, video, and communication systems are represented using sequences.

## Weather Forecasting – Temperature and rainfall data recorded daily form sequences used for prediction models.

## Stock Market Analysis – Prices of stocks and shares over time create sequences that help in trend analysis.

## Physics and Engineering – Motion, vibrations, and wave patterns are often modeled using mathematical sequences.

## Biology – DNA patterns and reproduction models involve sequences.

## Architecture and Art – Fibonacci sequences appear in designs, patterns, and natural proportions.

## Traffic and Queuing Systems – Arrival and departure of vehicles or customers are studied using sequences for optimization.

##

##    Extra Study Material Links:

- Sequence and Series - Difference, Definitions, Examples

- 9.1: Sequences - Mathematics LibreTexts

##    Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Ratio test 2.1.5
# Ratio test 2.1.5

## The topic is associated with the following course outcomes:

##

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

## CO4

## Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and

signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

9.6: Ratio and Root Tests - Mathematics LibreTexts

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Some monotone convergent and divergent sequences 2.1.2
# Some monotone convergent and divergent sequences 2.1.2

## The topic is associated with the following course outcomes:

## CO1

## Define the fundamentals of matrices, infinite series and differential equations.

## CO2

## Identify and distinguish the types of matrices, infinite series and differential equations.

##

##

##

## Applications of Sequences

## Some real-life applications of sequences are:

## Population Growth – The increase in population over time often follows a sequence pattern.

## Bank Interest and Investments – Compound interest calculations use geometric sequences to determine future value of money.

## Computer Algorithms – Sequences are used in programming, data structures, and analysis of algorithms.

## Signal Processing – Digital signals in audio, video, and communication systems are represented using sequences.

## Weather Forecasting – Temperature and rainfall data recorded daily form sequences used for prediction models.

## Stock Market Analysis – Prices of stocks and shares over time create sequences that help in trend analysis.

## Physics and Engineering – Motion, vibrations, and wave patterns are often modeled using mathematical sequences.

## Biology – DNA patterns and reproduction models involve sequences.

## Architecture and Art – Fibonacci sequences appear in designs, patterns, and natural proportions.

## Traffic and Queuing Systems – Arrival and departure of vehicles or customers are studied using sequences for optimization.

##

##    Extra Study Material Links:

- Sequence and Series - Difference, Definitions, Examples

- 9.1: Sequences - Mathematics LibreTexts

##    Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


## 🖥️ PRESENTATION SLIDES


# Chapter 2.1 - All Lecture Slides Text


## Unit 2 chapter 1 maths 1
### Slide 1
- UNIVERSITY INSTITUTE OF
- UIE
- Engineering Foundations-
- 1 to 5
- Bachelor of Engineering
- All Branches
- / SEMESTER-1
- Mathematics-I
- (
- 26SMT-121
- )
- Unit
- No.  2
- Chapter No.
- 1
- Topic
- : Sequence and Series
- Shivani
- Bansal and E5471                                                       Assistant Professor
- Academic Session
- 2026-27
- ODD Semester Jul-Dec
- 2026

### Slide 2
- Learning Objectives
- To
- understand the basic concept of
- Sequences and
- S
- eries
- along
- with
- various properties.
- 2. To
- understand the concept
- of convergence and divergence of series.
- 1

### Slide 3
- Sequences
- and Series
- Topic
- 1. Concept
- of
- Sequences
- Topic
- 2
- .
- Concept
- of
- Series
- Topic
- 3
- .
- Convergence and
- Divergence
- Figure-1
- source (google)
- 2

### Slide 4
- Concept of
- Sequences
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 3

### Slide 5
- Concept of
- Infinite Series
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 4

### Slide 6
- Convergence and Divergence of Series
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 5

### Slide 7
- Applications of
- Sequences
- 6
- Population Growth
- – The increase in population over time often follows a sequence pattern.
- Bank Interest and Investments
- – Compound interest calculations use geometric sequences to determine future value of money.
- Computer Algorithms
- – Sequences are used in programming, data structures, and analysis of algorithms.
- Signal Processing
- – Digital signals in audio, video, and communication systems are represented using sequences.
- Weather Forecasting
- – Temperature and rainfall data recorded daily form sequences used for prediction models.
- Stock Market Analysis
- – Prices of stocks and shares over time create sequences that help in trend analysis.
- Physics and Engineering
- – Motion, vibrations, and wave patterns are often
- modeled
- using mathematical sequences.
- Biology
- – DNA patterns and reproduction models involve sequences.
- Architecture and Art
- – Fibonacci sequences appear in designs, patterns, and natural proportions.
- Traffic and Queuing Systems
- – Arrival and departure of vehicles or customers are studied using sequences for optimization.

### Slide 8
- Summary of the Lecture
- Studied
- the
- basic concept of
- s
- equences and series
- along
- with
- various properties.
- 2.
- Learned the
- concept
- of convergence and divergence of series
- 7

### Slide 9
- Next Lecture
- 8
- Tests of Convergence
- Alternating series test
- Absolute convergence

### Slide 10
- Quiz
- 9
- 1.
- The sequence 1,
- 1, 2, 3, 5, 8,… is called
- :
- A) Arithmetic sequence
- B) Geometric sequence
- C) Fibonacci sequence
- D) Harmonic sequence
- 2.
- What is the next term in the
- sequence 2
- , 4, 6, 8,
- ?
- A) 9
- B) 10
- C) 12
- D) 14

### Slide 11
- Articles
- Sequence and Series - Difference, Definitions, Examples
- 9.1
- : Sequences - Mathematics
- LibreTexts
- 10

### Slide 12
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- nptel.ac.in/courses/122101003
- https
- ://
- youtu.be/VLv1adcoiWo?si=eQys9_YtLb5_ln00
- 11

### Slide 13
- Class-Wise
- Feedback
- 12
- https://forms.gle/yc7yfgLaTbYd5D4AA

### Slide 14
- Thank You
- For queries
- Email:
- shivanibansal.maths@cumail.in
- 13


---


================================================================================


# Chapter 2.2 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Absolute convergence of a series 2.2.6
# Absolute convergence of a series 2.2.6

## The topic is associated with the following course outcomes:

##

## CO4

## Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

## CO5

## Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series, and differential equations.

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and  signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

3.3: Convergence Tests - Mathematics LibreTexts

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Gauss test and Logarithmic test 2.2.2, 2.2.3
# Gauss test and Logarithmic test 2.2.2, 2.2.3

## The topic is associated with the following course outcomes:

##

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

## CO4

## Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

## CO5

## Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series, and differential equations.

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and  signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

3.3: Convergence Tests - Mathematics LibreTexts

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Integral test 2.2.4
# Integral test 2.2.4

## The topic is associated with the following course outcomes:

##

## CO4

## Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

## CO5

## Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series, and differential equations.

##

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and  signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

3.3: Convergence Tests - Mathematics LibreTexts

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Leibnitz test for Alternating series 2.2.5
# Leibnitz test for Alternating series 2.2.5

## The topic is associated with the following course outcomes:

##

## CO4

## Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

## CO5

## Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series, and differential equations.

##

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and  signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

3.3: Convergence Tests - Mathematics LibreTexts

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Raabe's test 2.2.1
# Raabe's test 2.2.1

## The topic is associated with the following course outcomes:

##

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

## CO4

## Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

##

##

##

## Applications of Infinite Series:

Infinite series are used in many real-life fields because they help represent complicated functions, model repeating processes, and approximate values accurately. Here are some important applications:

Engineering and Physics

Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid motion.

For example, Fourier Series helps engineers analyze vibrations, radio signals, and musical sounds.

Computer Science

Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and exponentials.

Example: calculators approximate

Finance and Economics

Infinite geometric series are used in loan calculations, annuities, and investment models.

Example: finding the present value of endless cash flows in perpetuities.

Signal Processing and Telecommunications

Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into frequencies.

This is important in technologies like Wi-Fi, MP3 compression, and television broadcasting.

Medicine and Biology

Infinite series help model population growth, spread of diseases, and medical imaging techniques such as MRI and CT scans.

Astronomy and Space Science

Scientists use series approximations to calculate planetary motion, satellite paths, and gravitational effects.

Architecture and Construction

Structural engineers use series solutions when analyzing bridges, buildings, and vibration resistance during earthquakes.

Weather Forecasting

Meteorologists use mathematical models involving series expansions to predict temperature, rainfall, and wind patterns.

Machine Learning and Artificial Intelligence

Optimization algorithms and probability models often rely on series approximations for efficient computation.

Everyday Electronics

Digital cameras, smartphones, and GPS systems use algorithms based on infinite series for image correction, navigation, and

signal accuracy. This idea is used in finance, digital systems, and probability calculations.

##

## Extra Study Material Links:

Raabe's Test -- from Wolfram MathWorld

nptel.ac.in/courses/122101003

## Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


## 🖥️ PRESENTATION SLIDES


# Chapter 2.2 - All Lecture Slides Text


## Unit 2 chapter 2 maths 1
### Slide 1
- UNIVERSITY INSTITUTE OF
- UIE
- Engineering Foundations-
- 1 to 5
- Bachelor of Engineering
- All Branches
- / SEMESTER-1
- Mathematics-I
- (
- 26SMT-121
- )
- Unit
- No.  2
- Chapter No.
- 2
- Topic
- : Tests of Convergence
- Shivani
- Bansal and E5471                                                       Assistant Professor
- Academic Session
- 2026-27
- ODD Semester Jul-Dec
- 2026

### Slide 2
- Learning Objectives
- To
- understand the basic
- Tests of Convergence and Divergence.
- 2. To
- understand the concept
- of Absolute convergence of series.
- 1

### Slide 3
- Tests of
- Convergence
- Topic
- 1.
- Raabe’s
- and Gauss Test
- Topic
- 2
- .
- Alternating series
- test
- Topic
- 3
- .
- Absolute convergence
- Figure-1
- source (google)
- 2

### Slide 4
- Tests of Convergence
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 3

### Slide 5
- Alternating series test
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 4

### Slide 6
- Absolute convergence
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 5

### Slide 7
- Applications of
- Series
- 6
- Engineering and Physics
- Infinite series are used to solve problems involving heat transfer, sound waves, electricity, and fluid
- motion. For
- example, Fourier Series helps engineers
- analyze
- vibrations, radio signals, and musical sounds
- .
- Computer Science
- Computers use series expansions to calculate values of functions like sine, cosine, logarithms, and
- exponentials. Example
- : calculators
- approximate
- Finance and Economics
- Infinite geometric series are used in loan calculations, annuities, and investment
- models. Example
- : finding the present value of endless cash flows in perpetuities
- .
- Signal Processing and Telecommunications
- Audio compression, image processing, and mobile communication use Fourier series and transforms to break signals into
- frequencies. This
- is important in technologies like Wi-Fi, MP3 compression, and television broadcasting
- .

### Slide 8
- Summary of the Lecture
- 1. Studied
- the
- basic
- Tests of Convergence
- 2.
- Learned the
- concept
- of Absolute convergence   of series
- 7

### Slide 9
- Quiz
- 8
- 1.
- Which test is most suitable for factorial expressions in series
- ?
- A) Root Test
- B) Ratio Test
- C) Integral Test
- D) Comparison Test
- 2.
- Which of the following series converges?
- A)
- ∑ 2^n
- </a:r><a:br><a:rPr lang="en-GB" dirty="0"/></a:br><a:r><a:rPr lang="en-GB" dirty="0"/><a:t>B) ∑
- 1\n
- </a:r><a:br><a:rPr lang="en-GB" dirty="0"/></a:br><a:r><a:rPr lang="en-GB" dirty="0"/><a:t>C) ∑
- 1\2^n
- </a:r><a:br><a:rPr lang="en-GB" dirty="0"/></a:br><a:r><a:rPr lang="en-GB" dirty="0"/><a:t>D) ∑
- n

### Slide 10
- Articles
- Sequence and Series - Difference, Definitions, Examples
- 9.1
- : Sequences - Mathematics
- LibreTexts
- 9

### Slide 11
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- nptel.ac.in/courses/122101003
- https
- ://
- youtu.be/VLv1adcoiWo?si=eQys9_YtLb5_ln00
- 10

### Slide 12
- Class-Wise
- Feedback
- 11
- https://forms.gle/yc7yfgLaTbYd5D4AA

### Slide 13
- Thank You
- For queries
- Email:
- shivanibansal.maths@cumail.in
- 12


---


================================================================================


# Chapter 3.1 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Bernoulli's LDE 3.1.8
# Bernoulli's LDE 3.1.8

## The topic is associated with the following course outcomes:

CO3

Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

## Applications of Bernoulli Differential Equations

## Bernoulli equations appear in a wide range of fields where systems involve nonlinear growth or decay. Key applications include:

## 1. Population Dynamics

## The Bernoulli equation models population growth with environmental constraints, e.g., logistic-type models with nonlinear growth terms.

## Example:

dPdt+rP=kP2\frac{dP}{dt} + rP = kP^2

## dtdP​+rP=kP2

## 2. Fluid Mechanics

## In certain fluid flow problems involving viscosity or drag, Bernoulli-type equations emerge (not to be confused with Bernoulli's principle).

## Example: The equation for velocity of a falling body with quadratic air resistance:

mdvdt+kv2=mg

## (can be reduced to Bernoulli form with some substitutions).

## 3. Electrical Circuits

## Nonlinear RC or RL circuits: When the resistance or inductance depends on the current or voltage (nonlinearly), Bernoulli equations can model the behavior.

## Example:

dIdt+aI=bIn\frac{dI}{dt} + aI = bI^n

## 4. Chemical Kinetics

## Certain reactions where the rate depends nonlinearly on concentration can be modeled with Bernoulli equations.

## Example:

dCdt=kC−rCn\frac{dC}{dt} = kC - rC^n

## 5. Heat Transfer

## Problems involving nonlinear heat loss or gain (e.g., radiation or convection terms proportional to a power of temperature) can lead to Bernoulli-type ODEs.

## 6. Finance and Economics

## Nonlinear growth of investments or debt repayment models with compound interest or taxation effects may lead to Bernoulli equations.

##

## Extra Study Material Links:

- https://tutorial.math.lamar.edu/classes/de/bernoulli.aspx

- https://brilliant.org/wiki/bernoullis-equation/

- BERNOULLI EQUATIONS

Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Exact Linear Differential equations 3.1.1
# Exact Linear Differential equations 3.1.1

##

## The topic is associated with the following course outcomes:

## CO1

## Define the fundamentals of matrices, infinite series and differential equations.

## CO2

## Identify and distinguish the types of matrices, infinite series and differential equations.

## Key Applications of Exact Differential Equations

## 1. Thermodynamics

## Context: Exact equations naturally arise in thermodynamic identities.

## Use: First law of thermodynamics involves differential forms:

dU=TdS−PdV

## Internal energy

UU

## , entropy

SS

## , and volume

VV

##  form an exact relationship — solving yields state functions like entropy, enthalpy.

## 2. Mechanics (Conservative Force Fields)

## Context: In a conservative force field, work done is path-independent.

## Use: The force field

F⃗=∇ϕ\vec{F} = \nabla \phi

##  leads to:

dW=Fxdx+Fydy=0dW = F_x dx + F_y dy = 0

## This is an exact equation where

ϕ(x,y)\phi(x, y)

##  is the potential energy.

## 3. Electrical Potential (Electrostatics)

## Context: The electric field

E⃗\vec{E}

## is conservative.

## Use: Field lines can be described by:

Exdx+Eydy=0

## This leads to finding electric potential

V(x,y)V(x, y)

## .

## 4. Fluid Mechanics

## Context: In irrotational, incompressible flows, velocity fields have potential functions.

## Use: Stream functions or velocity potentials satisfy:

u dx+v dy=0

## which is an exact differential form, allowing us to define

ϕ(x,y)\phi(x, y)

##  the velocity potential.

## 5. Heat and Mass Transfer

## Context: Steady-state diffusion problems often lead to exact forms.

## Use: Temperature or concentration profiles in a 2D field can be solved using potential theory, modeled by exact differentials.

## 6. Chemistry – State Functions

## Context: Chemical potential, enthalpy, and Gibbs free energy are state functions.

## Use: These are expressed as exact differentials involving temperature, pressure, and volume.

##  Extra Study Material Links:

- https://tutorial.math.lamar.edu/classes/de/exact.aspx

- https://calcworkshop.com/first-order-differential-equations/solving-exact-odes/

- EXACT EQUATIONS

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Integrating Factors _ Rule III, IV, V 3.1.5, 3.1.6
# Integrating Factors : Rule III, IV, V 3.1.5, 3.1.6

## The topic is associated with following course outcomes:

##

## CO2

## Identify and distinguish the types of matrices, infinite series and differential equations.

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

## Applications of Integrating Factors in Real Life

## Integrating factors are used across various disciplines to solve otherwise unsolvable differential equations that model complex systems. Below are some major applications:

## 1. Thermodynamics (First Law)

## Context: In thermodynamic systems, energy conservation involves heat, work, and internal energy.

## Use: Many thermodynamic processes can be described by differential equations that are not exact. Integrating factors make them solvable, particularly when deriving state functions like entropy and enthalpy.

## Example:

dQ=TdS,not exact unless you use integrating factor 1T

## 2. Electrostatics and Electromagnetism

## Context: Some electric field line integrals lead to non-exact equations.

## Use: Finding electric potential functions where integrating factors are used to transform path-dependent line integrals into state functions (exact).

## 3. Mechanical Systems (Conservation Laws)

## Context: Systems with friction, damping, or variable mass often yield non-exact forms.

## Use: Integrating factors help convert such problems into solvable equations for forces, velocities, or displacements.

## 4. Fluid Mechanics

## Context: Flow fields described by differential expressions that are not exact.

## Use: Integrating factors convert these into exact equations to determine potential functions or streamline functions in irrotational flow.

## 5. Chemical Engineering (Reactor Design)

## Context: Material or energy balances often yield non-exact differential equations.

## Use: Integrating factors are applied to solve for concentration or temperature profiles in reactors.

## 6. Economics (Utility and Production Functions)

## Context: Optimization and marginal analyses sometimes involve non-exact differentials.

## Use: Integrating factors can be applied to convert them into exact forms to find potential utility or production functions.

##     Extra Study Material Links:

- https://ecampusontario.pressbooks.pub/diffeq/chapter/2-4-integrating-factors/

- https://www.scribd.com/document/477096438/NON-EXACT-DE

- ode.pdf

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Integrating Factors_ Rule I and II 3.1.3, 3.1.4
# Integrating Factors: Rule I and II 3.1.3, 3.1.4

## The topic is associated with following course outcomes:

##

## CO2

## Identify and distinguish the types of matrices, infinite series and differential equations.

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

##

## Applications of Integrating Factors in Real Life

## Integrating factors are used across various disciplines to solve otherwise unsolvable differential equations that model complex systems. Below are some major applications:

## 1. Thermodynamics (First Law)

## Context: In thermodynamic systems, energy conservation involves heat, work, and internal energy.

## Use: Many thermodynamic processes can be described by differential equations that are not exact. Integrating factors make them solvable, particularly when deriving state functions like entropy and enthalpy.

## Example:

dQ=TdS,not exact unless you use integrating factor 1T

## 2. Electrostatics and Electromagnetism

## Context: Some electric field line integrals lead to non-exact equations.

## Use: Finding electric potential functions where integrating factors are used to transform path-dependent line integrals into state functions (exact).

## 3. Mechanical Systems (Conservation Laws)

## Context: Systems with friction, damping, or variable mass often yield non-exact forms.

## Use: Integrating factors help convert such problems into solvable equations for forces, velocities, or displacements.

## 4. Fluid Mechanics

## Context: Flow fields described by differential expressions that are not exact.

## Use: Integrating factors convert these into exact equations to determine potential functions or streamline functions in irrotational flow.

## 5. Chemical Engineering (Reactor Design)

## Context: Material or energy balances often yield non-exact differential equations.

## Use: Integrating factors are applied to solve for concentration or temperature profiles in reactors.

## 6. Economics (Utility and Production Functions)

## Context: Optimization and marginal analyses sometimes involve non-exact differentials.

## Use: Integrating factors can be applied to convert them into exact forms to find potential utility or production functions.

##     Extra Study Material Links:

- https://ecampusontario.pressbooks.pub/diffeq/chapter/2-4-integrating-factors/

- https://www.scribd.com/document/477096438/NON-EXACT-DE

- ode.pdf

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Leibnitz LDE 3.1.7
# Leibnitz LDE 3.1.7

## The topic is associated with the following course outcomes:

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

## CO4

## Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

## Applications of Leibniz Linear Differential Equations

##  These equations have a wide range of applications across physics, engineering, biology, and economics.

## 1. Newton's Law of Cooling

## Form:

dTdt+kT=kTenv\frac{dT}{dt} + kT = kT_{\text{env}}

## Context: Describes how the temperature

TT

## T of an object approaches the ambient temperature

TenvT_{\text{env}}

## Tenv​.

## Use: Used in food science, forensic science, and climate control systems.

## 2. Electrical Circuits (RC and RL circuits)

## Form:

dVdt+1RCV=1RCVin(t)\frac{dV}{dt} + \frac{1}{RC}V = \frac{1}{RC}V_{\text{in}}(t)

## Context: Governs the voltage across a resistor and capacitor (RC circuit).

## Use: Used in signal processing, filters, and analog electronics.

## 3. Mixing Problems (Chemistry/Engineering)

## Form:

dAdt+rA=rCin\frac{dA}{dt} + rA = rC_{\text{in}}

## Context: Models the concentration

AA

## A of a substance in a tank with continuous inflow and outflow.

## Use: Industrial mixing, water treatment, and drug dosing systems.

## 4. Economics – Simple Interest/Depreciation Models

## Form:

dMdt+rM=S(t)\frac{dM}{dt} + rM = S(t)

## Context: Describes how money accumulates or depreciates with regular income or spending.

## Use: Loan modeling, investment analysis, pension systems.

## 5. Population with Constant Harvesting

## Form:

dPdt+rP=H\frac{dP}{dt} + rP = H

## Context: Models population growth with a constant removal or harvesting rate.

## Use: Fisheries, wildlife management, and agriculture.

## 6. Motion with Linear Damping

## Form:

mdvdt+kv=F(t)m\frac{dv}{dt} + kv = F(t)

## Context: Velocity

vv

## v of an object subject to a force

F(t)F(t)

## F(t) and damping proportional to speed.

## Use: Vehicle dynamics, parachutes, mechanical damping systems.

## Extra Study Material Links:

- https://www.cuemath.com/calculus/linear-differential-equation/

- https://www.mathdoubts.com/leibniz-linear-differential-equation/

- Math 204 Differential Equations - Linear Equation and Bernoulli's Equation

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Non exact Linear Differential Equations 3.1.2
# Non exact Linear Differential Equations 3.1.2

## The topic is associated with following course outcomes:

##

## CO2

## Identify and distinguish the types of matrices, infinite series and differential equations.

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

##

## Applications of Integrating Factors in Real Life

## Integrating factors are used across various disciplines to solve otherwise unsolvable differential equations that model complex systems. Below are some major applications:

## 1. Thermodynamics (First Law)

## Context: In thermodynamic systems, energy conservation involves heat, work, and internal energy.

## Use: Many thermodynamic processes can be described by differential equations that are not exact. Integrating factors make them solvable, particularly when deriving state functions like entropy and enthalpy.

## Example:

dQ=TdS,not exact unless you use integrating factor 1T

## 2. Electrostatics and Electromagnetism

## Context: Some electric field line integrals lead to non-exact equations.

## Use: Finding electric potential functions where integrating factors are used to transform path-dependent line integrals into state functions (exact).

## 3. Mechanical Systems (Conservation Laws)

## Context: Systems with friction, damping, or variable mass often yield non-exact forms.

## Use: Integrating factors help convert such problems into solvable equations for forces, velocities, or displacements.

## 4. Fluid Mechanics

## Context: Flow fields described by differential expressions that are not exact.

## Use: Integrating factors convert these into exact equations to determine potential functions or streamline functions in irrotational flow.

## 5. Chemical Engineering (Reactor Design)

## Context: Material or energy balances often yield non-exact differential equations.

## Use: Integrating factors are applied to solve for concentration or temperature profiles in reactors.

## 6. Economics (Utility and Production Functions)

## Context: Optimization and marginal analyses sometimes involve non-exact differentials.

## Use: Integrating factors can be applied to convert them into exact forms to find potential utility or production functions.

##     Extra Study Material Links:

- https://ecampusontario.pressbooks.pub/diffeq/chapter/2-4-integrating-factors/

- https://www.scribd.com/document/477096438/NON-EXACT-DE

- ode.pdf

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


## 🖥️ PRESENTATION SLIDES


# Chapter 3.1 - All Lecture Slides Text


## Unit 3 chapter 1 maths 1
### Slide 1
- UNIVERSITY INSTITUTE OF
- UIE
- Engineering Foundations-
- 1 to 5
- Bachelor of Engineering
- All Branches
- / SEMESTER-1
- Mathematics-I
- (
- 26SMT-121
- )
- Unit
- No.
- 3
- Chapter No.
- 1
- Topic
- :
- First Order
- Linear Differential Equations
- Shivani
- Bansal and E5471                                                       Assistant Professor
- Academic Session
- 2026-27
- ODD Semester Jul-Dec
- 2026

### Slide 2
- Learning Objectives
- To understand the basic concept of Differential
- Equations along with various types.
- 2. To
- understand the concept
- of Leibnitz's and
- Bernoulli’s linear differential equations.
- 1

### Slide 3
- First order Linear Differential
- Equations
- Topic 1
- .
- Leibnitz's linear differential equations
- Topic
- 2
- .
- Bernoulli’s linear differential equations
- Topic 3.
- Exact Linear
- d
- ifferential equations
- Figure-1
- source (google)
- 2

### Slide 4
- Leibnitz Linear Differential Equation
- T
- he
- standard form of a
- Leibnitz’s linear
- differential equation
- is
- dy
- /dx
- +
- Py
- = Q,
- The
- P and Q
- are
- either
- numeric constants
- or functions of x
- .
- The
- general solution of the linear differential
- eqaution
- is
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 3

### Slide 5
- Bernoulli Linear Differential Equation
- T
- he
- standard form of a
- Bernoulli’s linear
- differential equation
- is
- The p(x)
- and
- q(x) are
- either
- numeric constants
- or functions of x
- .
- Use the
- substitution
- to
- convert this into a
- Leibnitz’s linear differential
- equation in terms of
- v
- .
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 4

### Slide 6
- Exact Linear differential equations
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 5

### Slide 7
- Non Exact differential
- equations
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 6

### Slide 8
- Non Exact differential
- equations
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 7

### Slide 9
- Applications
- of Differential Equations
- 8
- Field
- Example Application
- Type of Equation
- Physics
- Motion, heat, electromagnetism
- ODEs and PDEs
- Engineering
- Circuits, vibrations, heat transfer
- Linear/nonlinear ODEs
- Biology
- Population and disease
- modeling
- Logistic, SIR models
- Finance
- Option pricing and interest rates
- Black-Scholes, exponential
- Environment
- Pollution spread, climate change
- PDEs
- Space Science
- Rocket motion and orbits
- Newtonian ODEs
- AI/Tech
- Optimization and computer vision
- Gradient-based methods

### Slide 10
- Summary of the Lecture
- Studied
- the
- concept of Differential Equations
- along with
- various types.
- Learned
- the concept of Leibnitz's
- and Bernoulli’s
- linear
- differential equations.
- 9

### Slide 11
- Next Lecture
- 10
- Linear Differential Equations with constant coefficients
- Cauchy’s Linear
- Differential
- Equations
- Legendre’s Linear
- Differential Equations

### Slide 12
- Quiz
- 11

### Slide 13
- Articles
- https://
- tutorial.math.lamar.edu/classes/de/exact.aspx
- https://calcworkshop.com/first-order-differential-equations/solving-exact-odes/
- 12

### Slide 14
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- https://
- www.coursera.org/learn/ordinary-differential-equations
- https://
- www.coursera.org/learn/differential-equations-engineers
- https
- ://archive.nptel.ac.in/courses/111/106/111106100/?
- utm_source=chatgpt.com
- 13

### Slide 15
- Class-Wise
- Feedback
- 14
- https://forms.gle/yc7yfgLaTbYd5D4AA

### Slide 16
- Thank You
- For queries
- Email:
- shivanibansal.maths@cumail.in
- 15


---


================================================================================


# Chapter 3.2 - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Cauchy's Linear Differential Equations 3.2.7
# Cauchy's Linear Differential Equations 3.2.7

##

## The topic is associated with the following course outcomes:

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

CO5

Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series and differential equations.

## Why Cauchy–Euler Equations Are Important

They often arise when physical laws scale with distance or time, especially when the proportional change (not the absolute change) matters.

They describe scale-invariant systems, common in physics and engineering.

## Real-World Applications

## 1. Beam Deflection in Structural Engineering

Context: When the cross-section or loading changes with position in a way that’s proportional to

xx

.

Use: Describes deflection

y(x)y(x)

of tapered or non-uniform beams under certain loadings.

## 2. Fluid Mechanics

Context: Flow through pipes or around objects where the flow velocity or pressure varies logarithmically with distance.

Use: Cauchy-type equations model radially symmetric flow and boundary layer approximations.

## 3. Heat Transfer

Context: Cylindrical or spherical coordinates where temperature gradients depend on distance from the origin.

Use: Temperature profiles with radial symmetry (e.g., around a pipe or wire).

## 4. Elasticity and Material Science

Context: Stress and strain in cylinders or spheres where the internal forces vary with radius.

Use: Governs deformation in non-uniform materials and pressure vessels.

## 5. Electrical Engineering (Transmission Lines & Circuits)

Context: Certain transmission line problems where voltage/current depend on distance from a source and scale logarithmically.

Use: Models impedance or signal attenuation in coaxial cables or antennas.

## 6. Quantum Mechanics

Context: Schrödinger equation in spherical coordinates for central potentials.

Use: The radial part reduces to a Cauchy–Euler type ODE for specific potentials (e.g., Coulomb or harmonic oscillator).

## 7. Economics and Population Models

Context: Growth models where the rate of change is proportional to the current state and time.

Use: Models scale-invariant growth, such as investment or inflation.

## Extra Study Material Links:

- https://math.libretexts.org/Bookshelves/Differential_Equations/A_First_Course_in_Differential_Equations_for_Scientists_and_Engineers_(Herman)/02%3A_Second_Order_ODEs/2.05%3A_Cauchy-Euler_Equations

- https://www.geeksforgeeks.org/cauchy-euler-equation/

- Math 240: Cauchy-Euler Equation

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Legendre's Linear Differential Equations 3.2.8
# Legendre's Linear Differential Equations 3.2.8

##

## The topic is associated with the following course outcomes:

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

CO5

Apply appropriate method to determine the solution of some advanced level problems involving matrices, infinite series and differential equations.

## Why Legendre's Equation Is Important

## It appears naturally in problems involving Laplace's equation in spherical coordinates.

## The solutions form an orthogonal set of functions — critical in Fourier-Legendre expansions and separation of variables methods.

## Real-World Applications of Legendre’s Equation

## 1. Physics – Potential Theory

## Context: Solving Laplace’s equation in spherical coordinates (no angular dependence).

## Use: Describes electric, gravitational, and fluid potentials with spherical symmetry.

## 2. Electromagnetism

## Context: Electric potential outside a charge distribution.

## Use: Multipole expansion of the potential uses Legendre polynomials:

1∣r⃗−r⃗′∣=∑n=0∞r<nr>n+1Pn(cos⁡θ)

## 3. Quantum Mechanics

## Context: Solving the angular part of the Schrödinger equation for hydrogen atom.

## Use: Legendre polynomials describe angular wavefunctions when

m=0m = 0

## .

## 4. Astronomy and Geophysics

## Context: Modeling the Earth's gravitational or magnetic field.

## Use: Used in spherical harmonics, which are built from Legendre functions.

## 5. Acoustics

## Context: Sound wave propagation in spherical coordinates.

## Use: Legendre polynomials appear in solving the Helmholtz equation under spherical symmetry.

## 6. Numerical Methods and Approximation

## Context: Approximating functions over

[−1,1][-1, 1]

## .

## Use: Legendre polynomial interpolation and Gauss-Legendre quadrature useful for numerical integration.

## 7. General Relativity

## Context: Solving Einstein’s field equations with spherical symmetry.

## Use: Legendre functions appear in approximations of gravitational fields.

##

## Extra Study Material Links:

- https://www.geeksforgeeks.org/legendres-differential-equation/

- https://mathworld.wolfram.com/LegendreDifferentialEquation.html

- Microsoft Word - chapter 4

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Linear Differential equations with constant coefficients 3.2.1, 3.2.2
# Linear Differential equations with constant coefficients 3.2.1, 3.2.2

## The topic is associated with the following course outcomes:

## CO1

## Define the fundamentals of matrices, infinite series and differential equations.

## CO2

## Identify and distinguish the types of matrices, infinite series and  differential equations.

## CO3

## Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

##

## Applications of Higher-Order Linear Differential Equations with Constant Coefficients

## These equations are ubiquitous in modeling physical systems that involve oscillations, wave motion, circuits, and more.

##

## 1. Mechanical Vibrations

## Context: Modeling systems like springs, beams, and suspension systems.

## Equation:

md2xdt2+cdxdt+kx=F(t)m \frac{d^2x}{dt^2} + c \frac{dx}{dt} + kx = F(t)

## Use: Describes simple and damped harmonic motion. Solutions predict natural frequencies and damping behavior.

## 2. Electrical Circuits (RLC Circuits)

## Context: Series or parallel resistor-inductor-capacitor circuits.

## Equation:

Ld2qdt2+Rdqdt+1Cq=E(t)L \frac{d^2q}{dt^2} + R \frac{dq}{dt} + \frac{1}{C}q = E(t)

## Use: Models current or voltage over time; solutions show resonance, damping, and transient responses.

## 3. Structural Engineering (Beam Deflection)

## Context: Bending of beams under loads.

## Equation (Euler–Bernoulli beam theory):

EId4ydx4=q(x)

## Use: Determines deflection

y(x)y(x)

##  of beams under various loading conditions.

## 4. Control Systems

## Context: Transfer functions of systems with mass, inertia, or storage.

## Equation: Characteristic equation of the form:

anDn+⋯+a1D+a0=0a_n D^n + \cdots + a_1 D + a_0 = 0

## Use: Stability analysis, feedback loop design, system response tuning.

## 5. Acoustics and Vibrations

## Context: Sound waves in pipes or vibrating strings.

## Equation: Higher-order PDEs reduce to ODEs with constant coefficients after simplifications.

## Use: Predicts harmonic frequencies and sound wave propagation.

## 6. Quantum Mechanics and Optics

## Context: Schrödinger’s equation for constant potential regions:

d2ψdx2+k2ψ=0

## Use: Solves wave functions in bounded or step potential problems.

## 7. Economics (Dynamic Systems)

## Context: Dynamic models of investment, consumption, or market cycles.

## Equation: Linear differential equations represent growth models with feedback.

## Use: Predicts oscillations or exponential behavior in economic systems.

##   Extra Study Material Links:

- https://www.scribd.com/document/461196258/Linear-differential-equations-with-constant-coefficient

- https://math.libretexts.org/Bookshelves/Differential_Equations/Differential_Equations_for_Engineers_(Lebl)/2%3A_Higher_order_linear_ODEs/2.2%3A_Constant_coefficient_second_order_linear_ODEs

- Constant-Coefficient Linear Differential Equations

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Method of Variation of parameters 3.2.6
# Method of Variation of parameters 3.2.6

## The topic is associated with the following course outcomes:

CO3

Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

##

##

## EXAMPLE :

## Real-Life Applications

## 1. Mechanical Systems (Nonstandard Forces)

Context: A spring-mass system subjected to a non-periodic force like

F(t)=ln⁡tF(t) = \ln t

or

F(t)=tan⁡tF(t) = \tan t

Use: When

f(t)f(t)

isn't exponential or sinusoidal, variation of parameters is often the only method to find the particular integral.

## 2. Electrical Circuits

Context: RLC circuit with non-standard voltage input (e.g.,

V(t)=ln⁡tV(t) = \ln t

,

V(t)=tan⁡−1t.

Use: To find the particular solution (steady-state current or voltage), when

f(t)f(t)

is not suitable for undetermined coefficients.

## 3. Control Systems

Context: Response of systems to irregular inputs.

Use: System output prediction when input is not a basic sine, cosine, or exponential — for example, a ramp function or logarithmic input.

## 4. Vibrations in Mechanical Structures

Context: Structures or beams under non-uniform or complex loading.

Use: Helps determine displacement or stress when the load

f(x)f(x)

is irregular and doesn’t match standard forms.

## 5. Quantum Mechanics

Context: Solving the time-independent Schrödinger equation with non-trivial potentials.

Use: When potential energy functions lead to inhomogeneous differential equations with complex

f(x)f(x)

, variation of parameters can help construct wavefunctions.

## 6. Heat Conduction and Diffusion Problems

Context: Source terms that are logarithmic or nonlinear in nature.

Use: To find temperature or concentration profiles that can't be solved using simpler methods.

## Extra Study Material Links:

- https://tutorial.math.lamar.edu/classes/de/VariationofParameters.aspx

- https://www.mathsisfun.com/calculus/differential-equations-variation-parameters.html

- ode10.pdf

##

##  Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

##

---


### Rules to find Particular Integral 3.2.3, 3.2.4, 3.2.5
# Rules to find Particular Integral 3.2.3, 3.2.4, 3.2.5

## The topic is associated with the following course outcomes:

CO2

Identify and distinguish the types of matrices, infinite series and  differential equations.

CO3

Understand the various concepts and properties of matrices, infinite series, and differential equations used in solving mathematical problems.

CO4

Apply the principles of matrices, infinite series and differential equations to address engineering problems with real life applications.

## Applications of Particular Integrals in Differential Equations

In solving nonhomogeneous linear differential equations, the solution is made of two parts:

General Solution=Complementary Function (CF)+Particular Integral (PI)\text{General Solution} = \text{Complementary Function (CF)} + \text{Particular Integral (PI)}

Complementary Function (CF) solves the associated homogeneous equation (i.e., with the RHS = 0).

Particular Integral (PI) is a specific solution to the nonhomogeneous part (i.e., the forcing function on the RHS).

## Why Particular Integrals Are Important

Particular integrals represent the steady-state response of a system to an external input (forcing function). They're essential for predicting how systems behave under external influences like forces, voltages, or inputs.

## Key Applications by Field

## 1. Mechanical Vibrations

Context: Mass-spring-damper systems subjected to external forces.

Equation:

mx¨+cx˙+kx=F(t)

PI: Represents forced motion (e.g., from road bumps, engines, earthquakes).

Use: To find long-term behavior of structures or machines under repetitive force.

## 2. Electrical Engineering (RLC Circuits)

Context: Circuits with a voltage or current source.

Equation:

Lq¨+Rq˙+1Cq=V(t)

PI: Describes the steady-state voltage or current due to an AC or DC input.

Use: AC analysis, resonance, and filter design.

## 3. Control Systems

Context: System response to input signals.

Equation:

any(n)+⋯+a0y=f(t)

PI: Represents the output due to a specific input (e.g., a step or sinusoidal signal).

Use: Essential in determining system behavior under known inputs.

## 4. Heat Transfer and Diffusion

Context: Systems with heat sources.

Equation:

d2Tdx2=−Q(x)

PI: Represents the temperature distribution due to the heat source

Q(x)Q(x)

.

Use: Solving for steady-state temperature profiles.

## 5. Vibrations in Structures

Context: Beams or plates under distributed loads.

Equation:

EId4ydx4=q(x)

PI: Determines the deflection shape due to the load.

Use: Civil and mechanical engineering for designing safe structures.

## 6. Economics

Context: Economic models with external investment or consumption.

Equation:

y′′−3y′+2y=I(t)

PI: Models how the system behaves due to external inputs like investment.

##

##  Extra Study Material Links:

- https://www.scribd.com/document/461196258/Linear-differential-equations-with-constant-coefficient

- https://www.askiitians.com/iit-study-material/iit-jee-mathematics/algebra/differential-equation/methods-of-finding-p-i.aspx

- Constant-Coefficient Linear Differential Equations

##      Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

##

---


## 🖥️ PRESENTATION SLIDES


# Chapter 3.2 - All Lecture Slides Text


## Unit 3 chapter 2 maths 1
### Slide 1
- UNIVERSITY INSTITUTE OF
- UIE
- Engineering Foundations- 1
- to 5
- Bachelor of Engineering
- All Branches
- / SEMESTER-1
- Mathematics-I
- (
- 26SMT-121
- )
- Unit
- No.  3
- Chapter No. 2
- Topic : Higher order linear differential equations
- Shivani
- Bansal and E5471                                                       Assistant Professor
- Academic Session
- 2026-27
- ODD Semester Jul-Dec
- 2026

### Slide 2
- Learning Objectives
- 1. To
- understand
- Linear Differential Equations with constant
- coefficients.
- 2. To Learn the concept of
- Cauchy’s Linear
- Differential Equations.
- 3. To study
- Legendre’s
- Linear Differential
- Equations.
- 1

### Slide 3
- Higher
- Order
- Linear
- Differential Equations
- Topic 1
- .
- Linear Differential Equations with constant coefficients
- Topic
- 2.
- Cauchy’s
- Linear Differential Equations
- Topic
- 3.
- Legendre’s
- Linear Differential Equations
- 2

### Slide 4
- Linear
- Differential Equations
- with
- constant coefficients
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 3

### Slide 5
- Cauchy’s Linear Differential Equations
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 4

### Slide 6
- Additional / Recommended Readings:
- A Textbook Of Engineering
- Mathematics
- Sem
- -II by Usha Paul N. P. Bali (z-lib.org).pdf
- E.
- Kreyszig
- , Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing
- 5
- Legendre’s Differential Equations

### Slide 7
- Applications of Higher Order
- Linear
- Differential Equations
- 6
- Application Domain
- Type of Equation
- Order
- Real-World Example
- Mechanical Vibrations
- Damped harmonic oscillator
- 2nd order
- Car suspension, tuning forks
- Electrical Circuits
- RLC circuits
- 2nd order+
- Radios, filters, oscillators
- Beam Bending
- Euler–Bernoulli beam
- 4th order
- Bridges, skyscrapers
- Control Systems
- General linear ODEs
- Any order
- Drones, autopilots
- Thermal & Wave Systems
- PDEs → ODEs (via separation)
- 2nd/4th
- Heat exchangers, sound in pipes
- Pharmacokinetics
- Compartment models
- Higher
- Medicine dosage optimization

### Slide 8
- Summary of the Lecture
- Studied
- the
- basic concept
- of
- Linear
- Differential Equations with constant
- coefficients.
- 2
- .
- Learned the
- concept
- of
- Cauchy’s Linear Differential
- Equations.
- 3. Studied
- Legendre’s Linear Differential
- Equations.
- 7

### Slide 9
- Quiz
- 8

### Slide 10
- Articles
- https
- ://
- www.scribd.com/document/461196258/Linear-differential-equations-with-constant-coefficient
- https://math.libretexts.org/Bookshelves/Differential_Equations/Differential_Equations_for_Engineers_(Lebl)/2%3A_Higher_order_linear_ODEs/2.2%3A_Constant_coefficient_second_order_linear_ODEs
- 9

### Slide 11
- Faculty-curated videos, NPTEL, Coursera, LinkedIn, or other relevant learning resources
- 10
- https://
- www.coursera.org/learn/ordinary-differential-equations
- https://
- www.coursera.org/learn/differential-equations-engineers
- https
- ://archive.nptel.ac.in/courses/111/106/111106100/?
- utm_source=chatgpt.com

### Slide 12
- Class-Wise
- Feedback
- 11
- https://forms.gle/yc7yfgLaTbYd5D4AA

### Slide 13
- Thank You
- For queries
- Email:
- shivanibansal.maths@cumail.in
- 12


---


================================================================================


# Course Overview - Complete Study Material


## 📘 LECTURE NOTES & EXPLANATIONS


### Computer Requirements
# Computer Requirements

## Supported browsers

To learn more about CULMS general browser support policy, and to find information on Javascript, cookies, and other software, see the Browser Support Policy topic.

Desktop:

Chrome

Firefox

Safari

Edge

Mobile:

Mobile Safari & Google Chrome

---


### Course Information
# Course Information

Course pre-requisites: Knowledge of fundamental maths upto 10+2 standard

Credits: L: 3. T: 2 P: 0

Credits: 5

Structure of the Course:

The course has been divided into 3 units.

Assessment Model for Students:

Chandigarh University is committed towards excellence in academics and strives to continuously inspire

the academic environment through bringing transparency and efficiency in all the academic processes and

systems. Assessment is a vital part of the education process. Appropriate scheme of assessment helps determine

the usefulness of teaching learning processes. In CU, effectiveness of teaching and learning with students

is assessed through Internal Assessment including two Mid Semester Test (MST) and End Semester

Examination and every student assessment is to be mapped with the course outcomes defined for the

course.

The total assessment will be done out 100

The bifurcation is:

INTERNAL : 50 Marks

EXTERNAL: 50 Marks

Evaluation Type

Evaluation Instrument

Marks

Duration/Frequency

Final Weightage

Total Marks

Formative Assessment

Assignment

4 per Assignment

1 per unit

12

100

Formative Assessment

Quiz

3 per quiz

2 per semester

6

Interim Summative Assessments

MST-1

20

1 Hour

10

MST-2

20

1 Hour

10

Formative Assessment

Case study

10

1 per semester

10

Formative Assessment

Attendance

NA

NA

2

Semester End Examination

End Term Exam

50

3 Hours

50

---


### Course Introduction, Objectives and Outcomes
# Course Introduction, Objectives and Outcomes

Image Source: Internet

COURSE INTRODUCTION:

## The course provides a strong foundation in Basic Mathematics and equips the students with the essential mathematical tools for solving basic mathematics problems. The course begins with the theoretical study of Matrices which is widely utilized in all engineering applications. The students are then introduced to Infinite Series. The course further emphasizes on the concept of differential equations.

COURSE OBJECTIVE:

## a.  The objective of this course is to familiarize the prospective engineers with techniques in Matrices, Infinite Series and differential equations.

## b.      It aims to equip the students with standard concepts and tools at an intermediate to advanced level that will serve them well towards solving more advanced level of mathematics and applications that they would find useful in their respective disciplines.

COURSE OUTCOMES:

CO1

Define the fundamentals of matrices, Infinite Series and differential equations.

CO2

## Identify and distinguish the types of matrices, Infinite Series and differential equations.

## CO3

## Understand the various concepts and properties of matrices, Infinite Series, and differential equations used in solving mathematical problems.

## CO4

## Apply the principles of matrices, Infinite Series and differential equations to address engineering problems with real life applications.

## CO5

## Apply appropriate method to determine the solution of some advanced level problems involving matrices, Infinite Series and differential equations.

##

---


### Course Syllabus and Suggestive Readings
# Course Syllabus and Suggestive Readings

Subject Name: MATHEMATICS-I

Subject Code: 26SMT-121

##                Syllabus

##

##                                                                           Unit-I

Basics of Calculus & Matrices

Introduction to matrices, Types of matrices, Orthogonal and Unitary matrices, Rank of matrices, Elementary transformations, reduction to echelon form

Applications of Matrices

Consistency and solution of system of linear equations using matrices, Eigen values & Eigen Vectors, Linear dependence and independence of vectors, Cayley Hamilton Theorem (without proof), Inverse using Cayley Hamilton Theorem

Self-study topics for Advanced Learners

Diagonalization of Matrices, Modal matrix.

##   Unit-II

Sequence and  Series

Basics of sequences and series; Convergence and divergence of series; tests of convergence (without proofs); Comparison test, D’Alembert Ratio Test, Raabe’s Test, Gauss test, Logarithmic test, Cauchy’s root test, Integral test, Leibnitz test for alternating series and absolute convergence.

Self-study topics for Advanced Learners

Fourier series: Half range sine and cosine series.

##   Unit-III

First Order Linear Differential Equations

Introduction to Differential equations: order and degree, Exact Differential equations, Equations reducible to exact form by integrating factors, Leibniz’s linear differential equation and Bernoulli’s differential equation

Higher Order Linear Differential Equations

Methods of finding Complete Solutions for linear Differential Equation with constant coefficients: Complimentary functions, particular integrals: Method of variation of parameters to find the particular integrals, Linear Differential Equation with variable coefficient:  Cauchy’s homogeneous linear equation, Legendre’s linear equation.

Self-study topics for Advanced Learners

Clairaut’s form, Equations solvable for p, simultaneous linear equation with constant coefficients.

## TEXT BOOKS:

1.      E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi

2.      H.K.  Dass, Higher Engineering Mathematics, S Chand Publishers, 3rd revised edition, 2014.

3.      R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi.

##

## Reference Material:

1. B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi.

2. B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11thEdition.

3. N.P. Bali and Manish Goyal, A textbook of Engineering Mathematics, Laxmi Publications, Reprint, 2008.

Suggestive Reading Links :

- A Textbook Of Engineering Mathematics (PTU, Jalandhar) Sem-II by Usha Paul N. P. Bali (z-lib.org).pdf

- E. Kreyszig, Advanced Engineering Mathematics, John Wiley,10th Ed.2011., New Delhi - Bing

- R.K. Jain, and S.R.K. Iyengar, Advanced Engineering Mathematics, 3rd Edition, Narosa Publishing House, 2004, New Delhi - Bing

- B.V. Ramana Advanced Engineering Mathematics, McGraw Hill, July 2006, New Delhi. - Bing

- B. Thomas and, R.L., Finney, Calculus and Analytic Geometry, Pearson Education, 11th Edition - Bing

---


### Netiquette Guidelines
# Netiquette Guidelines

Netiquette is etiquette for the internet, guidelines and good practices for online communication in emails, discussion forums, and chat rooms.

Please practice the following guidelines when posting comments in the course:

- Format your text so it is easy to read. Try to use standard paragraph spacing, indentation, and legible font. Try to be consistent with your formatting, including font size, color, etc.

- Be concise and to the point in your communication. Limit discussion forum posts to a few paragraphs. Proofread and edit your work before posting.

- AVOID THE USE OF ALL CAPS as this may be interpreted as shouting. All lowercase letters also make text more difficult to read. Use standard punctuation. Remember what your teacher taught you in primary school about good punctuation and spelling.

- Avoid 'texting' abbreviations such as OMG.

- Avoid using humor and sarcasm, as they are often difficult to detect in written communication. It is okay to sparingly use emoticons to communicate subtleties or emotions that are more obvious in spoken communication.

- Flaming is not proper in our courses (a rant about someone or some topic). Practice civil discussion.

- Respect the privacy of communication within a course. Do not publicly forward the comments of classmates to others outside of the course.

- Stay on topic in a discussion.

- Be respectful.

- Participants have varying degrees of sensitivity, and that even some well-meaning constructive suggestions (e.g., comments about broken links, typo, and misspellings) may be misconstrued as public criticism. Therefore, please refrain from sharing comments in ways that might be misinterpreted, or do so privately when appropriate.

(Any violation to the above points if reported by the teacher may lead to disciplinary action against the student)

---


================================================================================

