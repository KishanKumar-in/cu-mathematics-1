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
