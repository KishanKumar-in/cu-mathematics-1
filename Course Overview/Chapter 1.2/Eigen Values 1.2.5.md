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