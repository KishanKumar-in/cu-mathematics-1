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