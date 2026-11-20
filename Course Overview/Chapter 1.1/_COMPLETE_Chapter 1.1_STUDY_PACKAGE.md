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
