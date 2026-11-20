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