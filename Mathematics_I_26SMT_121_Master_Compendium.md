# MATHEMATICS-I (CONT_26SMT-121 / 26SMT-121)
## Master Examination Definition, Theorem, Test & Formula Compendium — Units 1, 2 and 3

**Course:** Mathematics-I (`CONT_26SMT-121` / `26SMT-121`)  
**University:** Chandigarh University  
**Source Repository:** [`KishanKumar-in/cu-mathematics-1`](https://github.com/KishanKumar-in/cu-mathematics-1)  
**Master File:** `_COMPLETE_CONT_26SMT-121 __ MATHEMATICS-I_SEMESTER_MASTER.md`

---

### EXAMINER'S COVERAGE & METHODOLOGY NOTE

- **[DIRECTLY IN NOTES]**: Explicitly named, defined, or derived in CU repository lecture notes and presentation slides.
- **[RESTORED STANDARD EQUATION]**: Standard mathematical formula restored where an equation or slide image was unreadable or incomplete.
- **[EXAM SUPPORT]**: Proof outlines, working algorithms, standard derivations, and worked numericals added to make the course exam-ready for MSTs and End-Term exams.
- **⚠ Examiner’s flag**: Critical warnings highlighting common student traps, missing conditions, sign confusions, or faculty ambiguities.

### Official Course Syllabus Alignment

| Unit | Official Repository Syllabus Coverage |
| :--- | :--- |
| **Unit I** | Basics of matrices, types, orthogonal/unitary matrices, rank, elementary transformations, echelon form, consistency, eigenvalues/eigenvectors, linear dependence/independence, Cayley-Hamilton theorem and inverse using Cayley-Hamilton |
| **Unit II** | Sequences and series, convergence/divergence, comparison, ratio, Raabe, Gauss, logarithmic, root, integral and Leibniz tests, absolute convergence |
| **Unit III** | First-order differential equations, exact equations, integrating factors, Leibniz linear equation, Bernoulli equation, higher-order constant-coefficient equations, CF, PI, variation of parameters, Cauchy and Legendre equations |

> **Important Syllabus Distinction:** The official syllabus labels the Cayley-Hamilton theorem as "without proof" and convergence tests as "without proofs." Proof outlines and derivations are provided here for comprehension and derivation support. Diagonalization and Fourier series are identified as self-study topics for advanced learners.

---


# UNIT 1: MATRICES AND LINEAR ALGEBRA

Chapter 1.1: Matrices, elementary transformations, rank and normal form
1.1.1 Matrix and order of a matrix
[DIRECTLY IN NOTES] Definition
A matrix is a rectangular arrangement of elements, usually numbers, in rows and columns, enclosed in brackets or parentheses.
If a matrix has \(m\) rows and \(n\) columns, its order is \(m\times n\).
\[ A=[a_{ij}]_{m\times n} \]
Here, \(a_{ij}\) denotes the element in the \(i\)-th row and \(j\)-th column.
Example:
\[ A= \begin{bmatrix} 1&2&3\\ 4&5&6 \end{bmatrix} \]
The matrix has order \(2\times3\).
1.1.2 Types of matrices
Row matrix: A matrix having only one row.
\[ A=\begin{bmatrix}1&2&3\end{bmatrix} \]
Column matrix: A matrix having only one column.
\[ B=\begin{bmatrix}1\\2\\3\end{bmatrix} \]
Rectangular matrix: A matrix in which the number of rows and columns are unequal.
\[ m\ne n \]
Square matrix: A matrix having equal numbers of rows and columns.
\[ m=n \]
Zero or null matrix: A matrix in which every element is zero.
\[ O= \begin{bmatrix} 0&0\\ 0&0 \end{bmatrix} \]
Diagonal matrix: A square matrix in which all off-diagonal entries are zero.
\[ D= \begin{bmatrix} d_1&0&0\\ 0&d_2&0\\ 0&0&d_3 \end{bmatrix} \]
Scalar matrix: A diagonal matrix in which all diagonal entries are equal.
\[ A=kI \]
Identity matrix: A square matrix with ones on the principal diagonal and zeros elsewhere.
\[ I_n= \begin{bmatrix} 1&0&\cdots&0\\ 0&1&\cdots&0\\ \vdots&\vdots&\ddots&\vdots\\ 0&0&\cdots&1 \end{bmatrix} \]
Upper triangular matrix: All entries below the principal diagonal are zero.
Lower triangular matrix: All entries above the principal diagonal are zero.
Symmetric matrix [DIRECTLY IN NOTES]:
A square matrix \(A\) is symmetric if
\[ \boxed{A^T=A} \]
Skew-symmetric matrix [DIRECTLY IN NOTES]:
A square matrix \(A\) is skew-symmetric if
\[ \boxed{A^T=-A} \]
Consequently, every diagonal element of a real skew-symmetric matrix is zero.
Singular matrix [DIRECTLY IN NOTES]:
A square matrix is singular if
\[ \boxed{|A|=0} \]
Non-singular matrix [DIRECTLY IN NOTES]:
A square matrix is non-singular if
\[ \boxed{|A|\ne0} \]
Orthogonal matrix [DIRECTLY IN NOTES]:
A real square matrix \(A\) is orthogonal if
\[ \boxed{A^TA=AA^T=I} \]
Therefore:
\[ A^{-1}=A^T \]
Unitary matrix [RESTORED STANDARD EQUATION]:
A complex square matrix \(A\) is unitary if
\[ \boxed{A^*A=AA^*=I} \]
Here, \(A^*\) is the conjugate transpose.
For a real matrix, the unitary condition reduces to orthogonality.
Idempotent matrix [DIRECTLY IN NOTES]:
\[ \boxed{A^2=A} \]
Involutory matrix [DIRECTLY IN NOTES]:
\[ \boxed{A^2=I} \]
Nilpotent matrix [EXAM SUPPORT]:
A square matrix \(A\) is nilpotent if there exists a positive integer \(k\) such that
\[ \boxed{A^k=O} \]
The least such positive integer is called the index of nilpotency.
Transpose [DIRECTLY IN NOTES]:
The transpose of an \(m\times n\) matrix is the \(n\times m\) matrix obtained by interchanging rows and columns.
If
\[ A=[a_{ij}]_{m\times n} \]
then
\[ A^T=[a_{ji}]_{n\times m} \]
Properties:
\[ (A^T)^T=A \]
\[ (A+B)^T=A^T+B^T \]
\[ (AB)^T=B^TA^T \]
\[ (kA)^T=kA^T \]
Adjoint or adjugate [DIRECTLY IN NOTES]:
The adjugate of a square matrix is the transpose of its cofactor matrix.
\[ \operatorname{adj}(A)=[C_{ij}]^T \]
where \(C_{ij}\) is the cofactor of element \(a_{ij}\).
Important identity:
\[ \boxed{A\operatorname{adj}(A)=\operatorname{adj}(A)A=|A|I} \]
For a non-singular matrix:
\[ \boxed{A^{-1}=\frac{\operatorname{adj}(A)}{|A|}} \]
Other properties for an \(n\times n\) matrix:
\[ \operatorname{adj}(AB)=\operatorname{adj}(B)\operatorname{adj}(A) \]
\[ |\operatorname{adj}(A)|=|A|^{n-1} \]
\[ \operatorname{adj}(kA)=k^{n-1}\operatorname{adj}(A) \]
1.1.3 Trace of a matrix
[DIRECTLY IN NOTES] Definition
The trace of a square matrix is the sum of its principal diagonal entries.
For an \(n\times n\) matrix:
\[ \boxed{\operatorname{tr}(A)=\sum_{i=1}^{n}a_{ii}} \]
Example:
\[ A= \begin{bmatrix} 2&1&0\\ 3&4&5\\ 6&7&8 \end{bmatrix} \]
\[ \operatorname{tr}(A)=2+4+8 \]
\[ \boxed{\operatorname{tr}(A)=14} \]
Properties:
\[ \operatorname{tr}(kA)=k\operatorname{tr}(A) \]
\[ \operatorname{tr}(A+B)=\operatorname{tr}(A)+\operatorname{tr}(B) \]
\[ \operatorname{tr}(A-B)=\operatorname{tr}(A)-\operatorname{tr}(B) \]
\[ \boxed{\operatorname{tr}(AB)=\operatorname{tr}(BA)} \]
In general, matrix multiplication is not commutative:
\[ AB\ne BA \]
But the traces of \(AB\) and \(BA\) are equal when both products are defined and square.
1.1.4 Elementary row and column transformations
[DIRECTLY IN NOTES] Definition
Elementary transformations are operations on rows or columns that preserve the rank of a matrix.
Three elementary row operations:
Interchange two rows.
Multiply a row by a non-zero scalar.
Add a scalar multiple of one row to another row.
Notation:
\[ R_i\leftrightarrow R_j \]
\[ R_i\rightarrow kR_i,\qquad k\ne0 \]
\[ R_i\rightarrow R_i+kR_j \]
The same rules apply to columns:
\[ C_i\leftrightarrow C_j \]
\[ C_i\rightarrow kC_i,\qquad k\ne0 \]
\[ C_i\rightarrow C_i+kC_j \]
Working rules
Only multiply a row or column by a non-zero constant.
A row replacement must use the original or already updated row consistently.
Elementary transformations do not change rank.
Row operations are commonly used to obtain echelon form.
Both row and column operations may be used to obtain normal form.
⚠ Examiner’s flag: Multiplying a row by zero is not an elementary operation because it can destroy rank.
1.1.5 Rank of a matrix
[DIRECTLY IN NOTES] Definition
The rank of a matrix is the maximum number of linearly independent rows or columns. It is also the number of non-zero rows in a row echelon form.
Notation:
\[ \operatorname{rank}(A)=r \]
For an \(m\times n\) matrix:
\[ \boxed{0\le r\le\min(m,n)} \]
A matrix has rank \(r\) if:
At least one minor of order \(r\) is non-zero.
Every minor of order \(r+1\) and above is zero.
Special results:
Rank of a zero matrix is zero.
Rank of \(I_n\) is \(n\).
If an \(n\times n\) matrix has non-zero determinant, its rank is \(n\).
Row rank equals column rank.
Method 1: Row-echelon method
Write the matrix.
Use elementary row operations.
Create zeros below successive pivots.
Count non-zero rows.
That count is the rank.
Method 2: Minor method
Find non-zero minors of the largest possible order.
If an \(r\times r\) minor is non-zero, rank is at least \(r\).
Verify that all minors of order \(r+1\) are zero.
Then rank is \(r\).
Important rank inequalities [RESTORED STANDARD EQUATIONS]:
\[ \operatorname{rank}(AB)\le \min\{\operatorname{rank}(A),\operatorname{rank}(B)\} \]
For \(A\) of order \(m\times n\):
\[ \operatorname{rank}(A)\le\min(m,n) \]
For \(n\times n\) matrices \(A,B\):
\[ \operatorname{rank}(A)+\operatorname{rank}(B)-n \le\operatorname{rank}(AB) \]
1.1.6 Row echelon form (REF)
[DIRECTLY IN NOTES] Definition
A matrix is in row echelon form if:
Every row of zeros, if present, occurs below every non-zero row.
The first non-zero entry in each non-zero row, called the leading entry or pivot, occurs to the right of the pivot in the preceding row.
All entries below each pivot are zero.
Example:
\[ A= \begin{bmatrix} 1&2&3\\ 0&1&4\\ 0&0&2 \end{bmatrix} \]
This is in REF.
Algorithm to obtain REF
Start with the first column.
Choose a non-zero pivot.
Interchange rows if the pivot position is zero.
Use row operations to eliminate entries beneath the pivot.
Move to the next row and next pivot column.
Continue until echelon form is obtained.
Count non-zero rows to obtain rank.
1.1.7 Reduced row echelon form (RREF)
[RESTORED STANDARD EQUATION] Definition
A matrix is in reduced row echelon form if it is in REF and:
Every pivot equals 1.
Each pivot is the only non-zero entry in its column.
Example:
\[ A= \begin{bmatrix} 1&0&2&0\\ 0&1&-1&0\\ 0&0&0&1 \end{bmatrix} \]
Algorithm
Obtain REF.
Divide each pivot row by its pivot value.
Start from the last pivot.
Eliminate all entries above that pivot.
Continue upwards.
Verify each pivot is 1 and its column has zeros elsewhere.
Key fact: RREF is unique for a given matrix, whereas REF need not be unique.
1.1.8 Normal or canonical form
[DIRECTLY IN NOTES]
A matrix of rank \(r\) can be reduced using elementary row and column transformations to the normal form
\[ \boxed{ \begin{bmatrix} I_r&0\\ 0&0 \end{bmatrix} } \]
This form has \(r\) ones on the leading diagonal and all other entries zero.
For example, a rank-2 matrix of order \(3\times4\) has canonical form
\[ \begin{bmatrix} 1&0&0&0\\ 0&1&0&0\\ 0&0&0&0 \end{bmatrix} \]
Theorem [RESTORED STANDARD EQUATION]
Every \(m\times n\) matrix of rank \(r\) can be transformed to the canonical form
\[ J_r= \begin{bmatrix} I_r&0\\ 0&0 \end{bmatrix} \]
by elementary row and column operations.
Equivalently, there exist non-singular matrices \(P\) and \(Q\) such that
\[ \boxed{PAQ=J_r} \]
Here:
\(P\) is an \(m\times m\) non-singular matrix.
\(Q\) is an \(n\times n\) non-singular matrix.
\(J_r\) is an \(m\times n\) canonical matrix.
\(r=\operatorname{rank}(A)\).
Algorithm for finding \(P\) and \(Q\)
Start with \(A\).
Record every elementary row operation as left multiplication by an elementary matrix.
Record every elementary column operation as right multiplication by an elementary matrix.
Apply the operations until the matrix becomes \(J_r\).
The product of row elementary matrices gives \(P\).
The product of column elementary matrices gives \(Q\).
Verify \(PAQ=J_r\).
Important: An elementary row operation corresponds to left multiplication. An elementary column operation corresponds to right multiplication.
1.1.9 Solved numerical: rank and REF
Find the rank of
\[ A= \begin{bmatrix} 1&2&3\\ 2&4&6\\ 1&1&2 \end{bmatrix} \]
Apply:
\[ R_2\rightarrow R_2-2R_1 \]
\[ R_3\rightarrow R_3-R_1 \]
Then:
\[ A\sim \begin{bmatrix} 1&2&3\\ 0&0&0\\ 0&-1&-1 \end{bmatrix} \]
Interchange rows 2 and 3:
\[ A\sim \begin{bmatrix} 1&2&3\\ 0&-1&-1\\ 0&0&0 \end{bmatrix} \]
There are two non-zero rows.
\[ \boxed{\operatorname{rank}(A)=2} \]
Chapter 1.2: Systems of linear equations, dependence, eigenvalues and Cayley-Hamilton theorem
1.2.1 System of linear equations
[DIRECTLY IN NOTES] Definition
A system of \(m\) linear equations in \(n\) unknowns is a collection of equations of the form
\[ a_{i1}x_1+a_{i2}x_2+\cdots+a_{in}x_n=b_i \]
for \(i=1,2,\ldots,m\).
The matrix representation is
\[ \boxed{AX=B} \]
where
\[ A= \begin{bmatrix} a_{11}&a_{12}&\cdots&a_{1n}\\ a_{21}&a_{22}&\cdots&a_{2n}\\ \vdots&\vdots&\ddots&\vdots\\ a_{m1}&a_{m2}&\cdots&a_{mn} \end{bmatrix} \]
\[ X= \begin{bmatrix} x_1\\x_2\\\vdots\\x_n \end{bmatrix}, \qquad B= \begin{bmatrix} b_1\\b_2\\\vdots\\b_m \end{bmatrix} \]
\(A\): coefficient matrix.
\(X\): unknown-variable column matrix.
\(B\): constant column matrix.
1.2.2 Non-homogeneous system \(AX=B\)
Definition [DIRECTLY IN NOTES]
A system is non-homogeneous if at least one component of \(B\) is non-zero.
The augmented matrix is
\[ \boxed{[A\mid B]} \]
It is constructed by appending the right-hand-side column to the coefficient matrix.
1.2.3 Rouché-Capelli theorem (rank consistency theorem)
[DIRECTLY IN NOTES] Statement
A system of linear equations is consistent if and only if the rank of the coefficient matrix equals the rank of the augmented matrix.
\[ \boxed{\operatorname{rank}(A)=\operatorname{rank}([A\mid B])} \]
Let
\[ r=\operatorname{rank}(A), \quad r'=\operatorname{rank}([A\mid B]), \quad n=\text{number of unknowns} \]
There are three cases.
Case 1: Inconsistent system
\[ \boxed{r\ne r'} \]
The system has no solution.
Case 2: Unique solution
\[ \boxed{r=r'=n} \]
The system has exactly one solution.
Case 3: Infinitely many solutions
\[ \boxed{r=r'<n} \]
The system has infinitely many solutions, with \(n-r\) free parameters.
Algorithm for solving \(AX=B\)
Form \(A\).
Form augmented matrix \([A\mid B]\).
Apply elementary row operations.
Obtain echelon form.
Calculate \(\operatorname{rank}(A)\).
Calculate \(\operatorname{rank}([A\mid B])\).
Compare the ranks.
If consistent, compare common rank with the number of unknowns.
Back-substitute or read the RREF to obtain the solution.
1.2.4 Solved numerical: unique solution
Solve:
\[ x+y=5 \]
\[ 2x-y=1 \]
Matrix form:
\[ \begin{bmatrix} 1&1\\ 2&-1 \end{bmatrix} \begin{bmatrix} x\\y \end{bmatrix} = \begin{bmatrix} 5\\1 \end{bmatrix} \]
Augmented matrix:
\[ \left[ \begin{array}{cc|c} 1&1&5\\ 2&-1&1 \end{array} \right] \]
Apply:
\[ R_2\rightarrow R_2-2R_1 \]
\[ \left[ \begin{array}{cc|c} 1&1&5\\ 0&-3&-9 \end{array} \right] \]
Thus:
\[ -3y=-9 \]
\[ y=3 \]
Using the first equation:
\[ x+3=5 \]
\[ x=2 \]
\[ \boxed{x=2,\quad y=3} \]
There are two pivots and two unknowns, so the solution is unique.
1.2.5 Solved numerical: infinite solutions
Consider:
\[ x+y+z=3 \]
\[ 2x+2y+2z=6 \]
Augmented matrix:
\[ \left[ \begin{array}{ccc|c} 1&1&1&3\\ 2&2&2&6 \end{array} \right] \]
Apply:
\[ R_2\rightarrow R_2-2R_1 \]
\[ \left[ \begin{array}{ccc|c} 1&1&1&3\\ 0&0&0&0 \end{array} \right] \]
Here:
\[ r=r'=1<n=3 \]
Therefore there are infinitely many solutions.
Let \(y=s\) and \(z=t\). Then:
\[ x=3-s-t \]
\[ \boxed{(x,y,z)=(3-s-t,s,t)} \]
1.2.6 Solved numerical: inconsistent system
Consider:
\[ x+y=2 \]
\[ 2x+2y=5 \]
Augmented matrix:
\[ \left[ \begin{array}{cc|c} 1&1&2\\ 2&2&5 \end{array} \right] \]
Apply:
\[ R_2\rightarrow R_2-2R_1 \]
\[ \left[ \begin{array}{cc|c} 1&1&2\\ 0&0&1 \end{array} \right] \]
This produces the contradiction
\[ 0=1 \]
Thus:
\[ r\ne r' \]
\[ \boxed{\text{The system is inconsistent.}} \]
1.2.7 Homogeneous system \(AX=0\)
[DIRECTLY IN NOTES] Definition
A system is homogeneous if every constant on the right-hand side is zero.
\[ \boxed{AX=0} \]
The zero vector
\[ X=0 \]
always satisfies the system. This is the trivial solution.
Non-trivial solution: A solution for which at least one component of \(X\) is non-zero.
Theorem [RESTORED STANDARD EQUATION]
For an \(m\times n\) coefficient matrix \(A\), the homogeneous system has non-trivial solutions if and only if
\[ \boxed{\operatorname{rank}(A)<n} \]
Equivalently, the nullity is positive.
For a square matrix \(A\) of order \(n\), a non-trivial solution exists if and only if
\[ \boxed{|A|=0} \]
Nullity-rank theorem
\[ \boxed{\operatorname{rank}(A)+\operatorname{nullity}(A)=n} \]
where \(n\) is the number of columns.
Algorithm
Form the coefficient matrix \(A\).
Reduce \(A\) to REF or RREF.
Count pivot columns.
Identify free variables.
If every variable is a pivot variable, only the trivial solution exists.
If at least one free variable exists, non-trivial solutions exist.
Express dependent variables in terms of free variables.
1.2.8 Linear dependence and independence of vectors
[DIRECTLY IN NOTES] Definition
A collection of vectors \(v_1,v_2,\ldots,v_k\) is linearly independent if the equation
\[ c_1v_1+c_2v_2+\cdots+c_kv_k=0 \]
has only the trivial solution
\[ c_1=c_2=\cdots=c_k=0 \]
If a non-trivial set of coefficients satisfies this equation, the vectors are linearly dependent.
Equivalent criteria
For vectors placed as columns of a matrix \(A\):
Independent if \(\operatorname{rank}(A)=k\).
Dependent if \(\operatorname{rank}(A)<k\).
For \(n\) vectors in \(\mathbb R^n\):
\[ \boxed{|A|\ne0\Longleftrightarrow\text{independent}} \]
\[ \boxed{|A|=0\Longleftrightarrow\text{dependent}} \]
Important facts
Any set containing the zero vector is dependent.
Any set with more than \(n\) vectors in \(\mathbb R^n\) is dependent.
A subset of a linearly independent set is independent.
If one vector is a linear combination of the others, the set is dependent.
Numerical
Check the independence of
\[ v_1= \begin{bmatrix}1\\2\end{bmatrix}, \qquad v_2= \begin{bmatrix}3\\4\end{bmatrix} \]
Form
\[ A= \begin{bmatrix} 1&3\\ 2&4 \end{bmatrix} \]
Calculate determinant:
\[ |A|=1(4)-3(2) \]
\[ |A|=4-6=-2 \]
Since
\[ |A|\ne0 \]
\[ \boxed{v_1,v_2\text{ are linearly independent.}} \]
1.2.9 Eigenvalues and eigenvectors
[DIRECTLY IN NOTES] Definition
Let \(A\) be a square matrix. A non-zero vector \(X\) is an eigenvector of \(A\) corresponding to eigenvalue \(\lambda\) if
\[ \boxed{AX=\lambda X} \]
Rearranging:
\[ (A-\lambda I)X=0 \]
For a non-trivial solution \(X\), the determinant must vanish:
\[ \boxed{|A-\lambda I|=0} \]
This is called the characteristic equation.
The polynomial
\[ p(\lambda)=|A-\lambda I| \]
is the characteristic polynomial.
Algorithm to calculate eigenvalues
Identify the square matrix \(A\).
Form \(A-\lambda I\).
Calculate its determinant.
Set the determinant equal to zero.
Solve the characteristic equation.
The roots are eigenvalues.
Algorithm to calculate eigenvectors
For each eigenvalue \(\lambda\), form \(A-\lambda I\).
Solve
\[ (A-\lambda I)X=0 \]
Use row reduction.
Set free variables.
Obtain a non-zero vector.
Verify \(AX=\lambda X\).
Properties of eigenvalues [DIRECTLY IN NOTES]
For an \(n\times n\) matrix:
\[ \boxed{\operatorname{tr}(A)=\sum_{i=1}^{n}\lambda_i} \]
\[ \boxed{|A|=\prod_{i=1}^{n}\lambda_i} \]
Eigenvalues are counted with algebraic multiplicity.
Other important properties:
The eigenvalues of a triangular matrix are its diagonal entries.
The eigenvalues of \(A^T\) are the same as those of \(A\).
The eigenvalues of \(A^{-1}\), when \(A\) is invertible, are \(1/\lambda_i\).
The eigenvalues of \(kA\) are \(k\lambda_i\).
The eigenvalues of \(A^m\) are \(\lambda_i^m\).
The eigenvalues of \(A+cI\) are \(\lambda_i+c\).
If \(A\) is singular, at least one eigenvalue is zero.
If \(A\) is real symmetric, all its eigenvalues are real.
⚠ Examiner’s flag: The determinant is the product of eigenvalues and the trace is the sum, but these statements require a square matrix and eigenvalues counted with algebraic multiplicity.
1.2.10 Solved numerical: eigenvalues and eigenvectors
Find eigenvalues and eigenvectors of
\[ A= \begin{bmatrix} 4&1\\ 2&3 \end{bmatrix} \]
Step 1: Characteristic equation
\[ |A-\lambda I|=0 \]
\[ \begin{vmatrix} 4-\lambda&1\\ 2&3-\lambda \end{vmatrix}=0 \]
\[ (4-\lambda)(3-\lambda)-2=0 \]
\[ 12-7\lambda+\lambda^2-2=0 \]
\[ \lambda^2-7\lambda+10=0 \]
\[ (\lambda-5)(\lambda-2)=0 \]
Therefore:
\[ \boxed{\lambda_1=5,\quad\lambda_2=2} \]
Step 2: Eigenvector for \(\lambda=5\)
\[ (A-5I)X=0 \]
\[ \begin{bmatrix} -1&1\\ 2&-2 \end{bmatrix} \begin{bmatrix} x\\y \end{bmatrix} =0 \]
Thus:
\[ -x+y=0 \]
\[ y=x \]
Choose \(x=1\), \(y=1\).
\[ \boxed{X_1= \begin{bmatrix} 1\\1 \end{bmatrix}} \]
Step 3: Eigenvector for \(\lambda=2\)
\[ (A-2I)X=0 \]
\[ \begin{bmatrix} 2&1\\ 2&1 \end{bmatrix} \begin{bmatrix} x\\y \end{bmatrix} =0 \]
\[ 2x+y=0 \]
Choose \(x=1\), \(y=-2\).
\[ \boxed{X_2= \begin{bmatrix} 1\\-2 \end{bmatrix}} \]
Verification using trace and determinant
\[ \operatorname{tr}(A)=4+3=7=5+2 \]
\[ |A|=12-2=10=5(2) \]
Both properties are satisfied.
1.2.11 Cayley-Hamilton theorem
[DIRECTLY IN NOTES] Statement
Every square matrix satisfies its own characteristic equation.
If the characteristic polynomial of \(A\) is
\[ p(\lambda)= \lambda^n+c_1\lambda^{n-1}+\cdots+c_n \]
then
\[ \boxed{ p(A)=A^n+c_1A^{n-1}+\cdots+c_nI=O } \]
Important applications
Finding higher powers of a matrix.
Finding inverse of a non-singular matrix.
Reducing polynomial expressions in a matrix.
The official repository syllabus specifies Cayley-Hamilton without proof. The proof outline below is supplied as additional learning support.
Proof outline for \(2\times2\) matrices [EXAM SUPPORT]
Let
\[ A= \begin{bmatrix} a&b\\c&d \end{bmatrix} \]
Its characteristic equation is
\[ \lambda^2-(a+d)\lambda+(ad-bc)=0 \]
By direct multiplication,
\[ A^2-(a+d)A+(ad-bc)I=O \]
Hence:
\[ \boxed{A^2-\operatorname{tr}(A)A+|A|I=O} \]
This is the \(2\times2\) Cayley-Hamilton identity.
Proof outline for \(3\times3\) matrices [EXAM SUPPORT]
Let the characteristic polynomial be
\[ p(\lambda)=\lambda^3-c_1\lambda^2+c_2\lambda-c_3 \]
where
\[ c_1=\operatorname{tr}(A) \]
\[ c_3=\det(A) \]
and \(c_2\) is the sum of principal minors of order 2.
The characteristic identity is
\[ \boxed{A^3-c_1A^2+c_2A-c_3I=O} \]
The general theorem follows from the adjugate identity
\[ (\lambda I-A)\operatorname{adj}(\lambda I-A) =\det(\lambda I-A)I \]
Comparing coefficients and evaluating the resulting polynomial identity at \(A\) gives \(p(A)=O\). A full formal proof is beyond the syllabus requirement indicated by the repository.
1.2.12 Verification of Cayley-Hamilton theorem
Consider:
\[ A= \begin{bmatrix} 1&2\\ 3&4 \end{bmatrix} \]
Step 1: Characteristic polynomial
\[ |A-\lambda I|= \begin{vmatrix} 1-\lambda&2\\ 3&4-\lambda \end{vmatrix} \]
\[ =(1-\lambda)(4-\lambda)-6 \]
\[ =\lambda^2-5\lambda-2 \]
Therefore:
\[ p(\lambda)=\lambda^2-5\lambda-2 \]
Step 2: Substitute \(A\)
\[ p(A)=A^2-5A-2I \]
First calculate:
\[ A^2= \begin{bmatrix} 1&2\\ 3&4 \end{bmatrix} \begin{bmatrix} 1&2\\ 3&4 \end{bmatrix} = \begin{bmatrix} 7&10\\ 15&22 \end{bmatrix} \]
Then:
\[ 5A= \begin{bmatrix} 5&10\\ 15&20 \end{bmatrix} \]
\[ 2I= \begin{bmatrix} 2&0\\ 0&2 \end{bmatrix} \]
Thus:
\[ A^2-5A-2I = \begin{bmatrix} 7-5-2&10-10\\ 15-15&22-20-2 \end{bmatrix} \]
\[ = \begin{bmatrix} 0&0\\ 0&0 \end{bmatrix} \]
Hence:
\[ \boxed{A^2-5A-2I=O} \]
The theorem is verified.
1.2.13 Finding inverse using Cayley-Hamilton theorem
From the verified result:
\[ A^2-5A-2I=O \]
Multiply by \(A^{-1}\):
\[ A-5I-2A^{-1}=O \]
Rearrange:
\[ 2A^{-1}=A-5I \]
\[ A^{-1}=\frac12(A-5I) \]
Substitute:
\[ A^{-1} = \frac12 \left( \begin{bmatrix} 1&2\\ 3&4 \end{bmatrix} - \begin{bmatrix} 5&0\\ 0&5 \end{bmatrix} \right) \]
\[ A^{-1}= \frac12 \begin{bmatrix} -4&2\\ 3&-1 \end{bmatrix} \]
\[ \boxed{ A^{-1}= \begin{bmatrix} -2&1\\ \frac32&-\frac12 \end{bmatrix} } \]
1.2.14 Finding higher powers using Cayley-Hamilton
From
\[ A^2-5A-2I=O \]
we obtain:
\[ A^2=5A+2I \]
Multiply by \(A\):
\[ A^3=5A^2+2A \]
Substitute \(A^2=5A+2I\):
\[ A^3=5(5A+2I)+2A \]
\[ \boxed{A^3=27A+10I} \]
Multiply again by \(A\):
\[ A^4=27A^2+10A \]
\[ A^4=27(5A+2I)+10A \]
\[ \boxed{A^4=145A+54I} \]
General algorithm
Calculate the characteristic polynomial.
Replace powers using the Cayley-Hamilton identity.
Express \(A^n\) as a linear combination of lower powers.
Repeatedly substitute until the required power is obtained.
⚠ Examiner’s flag: The formula \(A^{-1}\) obtained from Cayley-Hamilton is valid only when \(\det(A)\ne0\). A singular matrix has no inverse.

# UNIT 2: SEQUENCES AND INFINITE SERIES

Chapter 2.1: Sequences and infinite series
2.1.1 Sequence
[DIRECTLY IN NOTES] Definition
A sequence is an ordered list of numbers arranged according to a definite rule.
It is represented by
\[ \{a_n\}_{n=1}^{\infty} \]
or
\[ a_1,a_2,a_3,\ldots \]
A sequence is a function whose domain is usually the positive integers.
2.1.2 Types of sequences
Bounded above
A sequence is bounded above if there exists a real number \(M\) such that
\[ a_n\le M \]
for all \(n\).
Bounded below
A sequence is bounded below if there exists \(m\in\mathbb R\) such that
\[ a_n\ge m \]
for all \(n\).
Bounded
A sequence is bounded if there exists \(M>0\) such that
\[ \boxed{|a_n|\le M} \]
for all \(n\).
Monotonically increasing
\[ a_{n+1}\ge a_n \]
for every \(n\).
Strictly increasing
\[ a_{n+1}>a_n \]
Monotonically decreasing
\[ a_{n+1}\le a_n \]
Strictly decreasing
\[ a_{n+1}<a_n \]
Convergent sequence
A sequence \(a_n\) converges to \(L\) if
\[ \boxed{\lim_{n\to\infty}a_n=L} \]
Formally, for every \(\varepsilon>0\), there exists \(N\) such that
\[ n\ge N\implies |a_n-L|<\varepsilon \]
Divergent sequence
A sequence is divergent if it has no finite limit.
Oscillatory sequence
A sequence is oscillatory when its terms fluctuate rather than approach a single finite limit. Oscillation itself does not always imply divergence: an oscillating sequence can converge if the amplitude tends to zero.
2.1.3 Monotone Convergence Theorem
[DIRECTLY IN NOTES] Theorem
Every monotone increasing sequence that is bounded above converges.
Every monotone decreasing sequence that is bounded below converges.
More precisely:
Increasing and bounded above \(\Rightarrow\) convergent to its supremum.
Decreasing and bounded below \(\Rightarrow\) convergent to its infimum.
Conditions
\[ a_{n+1}\ge a_n \quad\text{and}\quad a_n\le M \]
or
\[ a_{n+1}\le a_n \quad\text{and}\quad a_n\ge m \]
Proof outline [EXAM SUPPORT]
For an increasing bounded sequence, the set of its terms has a least upper bound \(L\). By the definition of supremum, for every \(\varepsilon>0\), some term \(a_N\) satisfies \(L-\varepsilon<a_N\le L\). Since the sequence is increasing, every later term satisfies the same inequality. Hence the sequence converges to \(L\).
The decreasing case follows using the infimum.
2.1.4 Solved numerical: convergence of a sequence
Consider:
\[ a_n=\frac{2n+1}{n+3} \]
Divide numerator and denominator by \(n\):
\[ a_n=\frac{2+1/n}{1+3/n} \]
Taking limit:
\[ \lim_{n\to\infty}a_n = \frac{2+0}{1+0} \]
\[ \boxed{\lim_{n\to\infty}a_n=2} \]
The sequence is convergent.
2.1.5 Infinite series
[DIRECTLY IN NOTES] Definition
An infinite series is the sum of the terms of an infinite sequence.
\[ \boxed{\sum_{n=1}^{\infty}a_n} \]
The \(n\)-th partial sum is
\[ S_n=a_1+a_2+\cdots+a_n \]
The series converges to \(S\) if
\[ \boxed{\lim_{n\to\infty}S_n=S} \]
It diverges if the limit does not exist as a finite number.
Necessary condition for convergence
If
\[ \sum_{n=1}^{\infty}a_n \]
converges, then
\[ \boxed{\lim_{n\to\infty}a_n=0} \]
The converse is not true.
For example:
\[ \lim_{n\to\infty}\frac1n=0 \]
but
\[ \sum_{n=1}^{\infty}\frac1n \]
diverges.
⚠ Examiner’s flag: Showing that the terms tend to zero is not enough to prove series convergence.
2.1.6 Geometric series
A geometric series is
\[ a+ar+ar^2+ar^3+\cdots \]
Its first \(n\) terms sum to
\[ S_n=\frac{a(1-r^n)}{1-r}, \qquad r\ne1 \]
For the infinite geometric series:
\[ \boxed{ \sum_{n=0}^{\infty}ar^n=\frac{a}{1-r} \quad\text{if }|r|<1 } \]
Conditions:
\(|r|<1\): converges to \(a/(1-r)\).
\(|r|>1\): diverges.
\(r=1\): diverges unless \(a=0\).
\(r=-1\): oscillates and does not converge unless \(a=0\).
Solved numerical
Evaluate:
\[ 3+1.5+0.75+\cdots \]
Here:
\[ a=3,\quad r=\frac12 \]
Since \(|r|<1\), the series converges.
\[ S=\frac{3}{1-\frac12} \]
\[ \boxed{S=6} \]
2.1.7 \(p\)-series or hyperharmonic series
[DIRECTLY IN NOTES] Definition
A \(p\)-series is
\[ \boxed{ \sum_{n=1}^{\infty}\frac1{n^p} } \]
Convergence conditions:
\[ \boxed{ p>1\Rightarrow\text{convergent} } \]
\[ \boxed{ p\le1\Rightarrow\text{divergent} } \]
Examples:
\[ \sum_{n=1}^{\infty}\frac1{n^2} \]
converges.
\[ \sum_{n=1}^{\infty}\frac1n \]
diverges.
2.1.8 Harmonic series
\[ \boxed{ 1+\frac12+\frac13+\frac14+\cdots } \]
The harmonic series diverges, even though its individual terms approach zero.
2.1.9 Solved numerical: \(p\)-series classification
Determine the nature of
\[ \sum_{n=1}^{\infty}\frac1{n^{3/2}} \]
Here:
\[ p=\frac32>1 \]
Therefore, by the \(p\)-series criterion:
\[ \boxed{\text{The series converges.}} \]
Determine the nature of
\[ \sum_{n=1}^{\infty}\frac1{\sqrt n} \]
Here:
\[ p=\frac12\le1 \]
Therefore:
\[ \boxed{\text{The series diverges.}} \]
Chapter 2.2: Tests for convergence of positive-term series
General assumptions
For the standard positive-term tests, assume
\[ a_n\ge0 \]
for all sufficiently large \(n\), unless a test explicitly allows a more general sign pattern.
A series of non-negative terms has partial sums that are monotonically non-decreasing. It converges if and only if those partial sums are bounded above.
2.2.1 Direct comparison test
[DIRECTLY IN NOTES] Theorem
Let \(a_n,b_n\ge0\) for all sufficiently large \(n\).
If
\[ 0\le a_n\le b_n \]
then:
If \(\sum b_n\) converges, then \(\sum a_n\) converges.
If \(\sum a_n\) diverges, then \(\sum b_n\) diverges.
Step-by-step algorithm
Identify the target series.
Compare its general term with a known series.
Establish a valid inequality for all sufficiently large \(n\).
Use the known convergence or divergence result.
State the conclusion.
Solved numerical
Test:
\[ \sum_{n=1}^{\infty}\frac1{n^2+3} \]
Since:
\[ n^2+3>n^2 \]
we obtain:
\[ 0<\frac1{n^2+3}<\frac1{n^2} \]
And:
\[ \sum_{n=1}^{\infty}\frac1{n^2} \]
converges because \(p=2>1\).
Therefore:
\[ \boxed{ \sum_{n=1}^{\infty}\frac1{n^2+3} \text{ converges.} } \]
2.2.2 Limit comparison test
[DIRECTLY IN NOTES] Theorem
Let \(a_n>0\) and \(b_n>0\) eventually, and suppose
\[ L=\lim_{n\to\infty}\frac{a_n}{b_n} \]
exists.
If \(0<L<\infty\), the two series have the same nature.
If \(L=0\) and \(\sum b_n\) converges, then \(\sum a_n\) converges.
If \(L=\infty\) and \(\sum b_n\) diverges, then \(\sum a_n\) diverges.
Algorithm
Select a standard comparison term \(b_n\).
Calculate \(\lim a_n/b_n\).
Simplify the limit.
If it is a finite positive number, conclude both series behave alike.
If zero or infinity, use the corresponding one-sided comparison implication carefully.
Solved numerical
Test:
\[ \sum_{n=1}^{\infty}\frac{3n+2}{n^3+1} \]
Compare with:
\[ b_n=\frac1{n^2} \]
Calculate:
\[ L=\lim_{n\to\infty} \frac{\frac{3n+2}{n^3+1}}{\frac1{n^2}} \]
\[ L=\lim_{n\to\infty} \frac{3n^3+2n^2}{n^3+1} \]
\[ \boxed{L=3} \]
Since \(0<L<\infty\) and \(\sum1/n^2\) converges:
\[ \boxed{\text{The given series converges.}} \]
2.2.3 D'Alembert's ratio test
[DIRECTLY IN NOTES] Theorem
For a positive-term series \(\sum a_n\), define
\[ L=\lim_{n\to\infty}\frac{a_{n+1}}{a_n} \]
when the limit exists.
\(L<1\): the series converges.
\(L>1\): the series diverges.
\(L=1\): the test is inconclusive.
For a general series, the absolute version uses
\[ L=\lim_{n\to\infty}\left|\frac{a_{n+1}}{a_n}\right| \]
Step-by-step algorithm
Write \(a_n\).
Write \(a_{n+1}\).
Form the ratio.
Take the absolute value if the series is not known to be positive.
Simplify factorials and powers.
Take the limit.
Apply the exact three-case rule.
Solved numerical
Test:
\[ \sum_{n=1}^{\infty}\frac{n}{3^n} \]
General term:
\[ a_n=\frac{n}{3^n} \]
Next term:
\[ a_{n+1}=\frac{n+1}{3^{n+1}} \]
Ratio:
\[ \frac{a_{n+1}}{a_n} = \frac{n+1}{3^{n+1}}\cdot\frac{3^n}{n} \]
\[ =\frac{n+1}{3n} \]
Taking limit:
\[ L=\lim_{n\to\infty}\frac{n+1}{3n} \]
\[ \boxed{L=\frac13<1} \]
Therefore:
\[ \boxed{\text{The series converges.}} \]
2.2.4 Cauchy's root test
[DIRECTLY IN NOTES] Theorem
For a series \(\sum a_n\), define
\[ L=\limsup_{n\to\infty}\sqrt[n]{|a_n|} \]
If the ordinary limit exists, it can be used in place of the limsup.
\(L<1\): absolutely convergent.
\(L>1\): divergent.
\(L=1\): inconclusive.
Algorithm
Take the absolute value of the general term.
Take its \(n\)-th root.
Simplify the root.
Evaluate the limit or limsup.
Apply the three cases.
Solved numerical
Test:
\[ \sum_{n=1}^{\infty}\left(\frac25\right)^n \]
\[ a_n=\left(\frac25\right)^n \]
\[ \sqrt[n]{a_n}=\frac25 \]
Therefore:
\[ L=\frac25<1 \]
\[ \boxed{\text{The series converges.}} \]
2.2.5 When ratio and root tests fail
If the calculated value equals 1, neither the ratio test nor the root test decides convergence.
⚠ Examiner’s flag: Do not write “divergent” when \(L=1\). The correct conclusion is “test is inconclusive.” Use another test.
Chapter 2.3: Advanced convergence tests
2.3.1 Raabe's test
[DIRECTLY IN NOTES] Theorem
For a positive-term series \(\sum a_n\), define
\[ \boxed{ R=\lim_{n\to\infty} n\left(\frac{a_n}{a_{n+1}}-1\right) } \]
when the limit exists.
\(R>1\): convergent.
\(R<1\): divergent.
\(R=1\): inconclusive.
This is especially useful when D'Alembert's ratio test gives 1.
Algorithm
Calculate \(a_{n+1}\).
Form \(a_n/a_{n+1}\).
Subtract 1.
Multiply by \(n\).
Take the limit.
Apply the Raabe conditions.
Solved numerical
Test:
\[ \sum_{n=1}^{\infty}\frac1{n^p} \]
Here:
\[ a_n=\frac1{n^p} \]
\[ \frac{a_n}{a_{n+1}} = \frac{(n+1)^p}{n^p} = \left(1+\frac1n\right)^p \]
Thus:
\[ R=\lim_{n\to\infty} n\left[\left(1+\frac1n\right)^p-1\right] \]
Using the first-order expansion:
\[ \left(1+\frac1n\right)^p = 1+\frac pn+O\left(\frac1{n^2}\right) \]
\[ R=p \]
Hence:
\(p>1\): convergent.
\(p<1\): divergent.
\(p=1\): inconclusive by Raabe, but the harmonic series diverges.
2.3.2 Gauss's test
[DIRECTLY IN NOTES] Standard form restored
For a positive-term series, suppose
\[ \frac{a_n}{a_{n+1}} = 1+\frac{\alpha}{n} +O\left(\frac1{n^{1+\delta}}\right) \]
for some \(\delta>0\).
Then:
\(\alpha>1\): convergent.
\(\alpha\le1\): divergent.
A commonly used equivalent formulation is
\[ \frac{a_n}{a_{n+1}} = 1+\frac{\alpha}{n}+\frac{\beta_n}{n^{1+\delta}} \]
where \(\beta_n\) is bounded.
The threshold \(\alpha=1\) is divergent in this stated version.
Working rule
Form \(a_n/a_{n+1}\).
Expand for large \(n\).
Identify the coefficient of \(1/n\).
Apply the Gauss threshold.
Check that the remainder satisfies the required boundedness/order condition.
Example
\[ a_n=\frac1{n^p} \]
Then:
\[ \frac{a_n}{a_{n+1}} = \left(1+\frac1n\right)^p = 1+\frac pn+O(n^{-2}) \]
Thus \(\alpha=p\).
\[ \boxed{p>1\Rightarrow\text{convergent};\quad p\le1\Rightarrow\text{divergent}} \]
2.3.3 Logarithmic test
[DIRECTLY IN NOTES] Standard form restored
One common logarithmic test for positive-term series is:
\[ \boxed{ L=\lim_{n\to\infty} \frac{\log(1/a_n)}{\log n} } \]
when the limit exists and \(a_n\) is eventually between 0 and 1.
\(L>1\): convergent.
\(L<1\): divergent.
\(L=1\): inconclusive.
This test compares the term with a power \(1/n^p\).
Algorithm
Ensure \(0<a_n<1\) eventually.
Calculate \(\log(1/a_n)\).
Divide by \(\log n\).
Take the limit.
Apply the three-case rule.
Example
\[ a_n=\frac1{n^p} \]
Then:
\[ \log\left(\frac1{a_n}\right)=p\log n \]
Therefore:
\[ L=\lim_{n\to\infty}\frac{p\log n}{\log n}=p \]
So:
\(p>1\): convergent.
\(p<1\): divergent.
\(p=1\): inconclusive by this test, but harmonic series diverges.
⚠ Examiner’s flag: There are several variants called logarithmic tests in engineering-mathematics texts. The exact version in your faculty's slide must be followed if its notation differs. The form above is a standard power-comparison logarithmic test.
2.3.4 Cauchy's integral test
[DIRECTLY IN NOTES] Theorem
Suppose \(f(x)\) is positive, continuous and decreasing for \(x\ge N\), and
\[ a_n=f(n) \]
Then:
\[ \boxed{ \sum_{n=N}^{\infty}a_n \text{ converges} \Longleftrightarrow \int_N^\infty f(x)\,dx \text{ converges} } \]
Conditions
\(f(x)>0\).
\(f(x)\) is continuous.
\(f(x)\) is monotonically decreasing.
\(a_n=f(n)\).
Algorithm
Express \(a_n\) as \(f(n)\).
Verify positivity.
Verify continuity.
Verify decreasing behaviour for sufficiently large \(x\).
Evaluate the improper integral.
Determine whether it has a finite value.
Solved numerical
Test:
\[ \sum_{n=2}^{\infty}\frac1{n(\log n)^p} \]
Take:
\[ f(x)=\frac1{x(\log x)^p} \]
For \(p>0\), this is eventually positive, continuous and decreasing.
Evaluate:
\[ \int_2^\infty\frac{dx}{x(\log x)^p} \]
Let:
\[ u=\log x,\quad du=\frac{dx}{x} \]
Therefore:
\[ \int_{\log2}^{\infty}\frac{du}{u^p} \]
This integral converges if and only if
\[ p>1 \]
Hence:
\[ \boxed{ \sum_{n=2}^{\infty}\frac1{n(\log n)^p} \text{ converges if }p>1 } \]
It diverges for \(p\le1\).
Chapter 2.4: Alternating series and absolute convergence
2.4.1 Alternating series
Definition [DIRECTLY IN NOTES]
An alternating series is a series whose terms alternate in sign.
\[ \boxed{ \sum_{n=1}^{\infty}(-1)^{n-1}b_n } \]
where \(b_n\ge0\).
2.4.2 Leibniz's alternating series test
[DIRECTLY IN NOTES] Theorem
The alternating series
\[ \sum_{n=1}^{\infty}(-1)^{n-1}b_n \]
converges if:
\(b_n\ge0\).
\(b_{n+1}\le b_n\) for all sufficiently large \(n\).
\(\lim_{n\to\infty}b_n=0\).
Then the series converges.
Remainder estimate
If \(S\) is the sum and \(S_n\) is the \(n\)-th partial sum, then
\[ \boxed{|S-S_n|\le b_{n+1}} \]
Algorithm
Express the series as alternating signs times positive terms.
Identify \(b_n\).
Verify positivity.
Prove monotonic decrease.
Verify limit zero.
State convergence.
Use the next term to bound truncation error.
Solved numerical
Test:
\[ 1-\frac12+\frac13-\frac14+\cdots \]
Here:
\[ b_n=\frac1n \]
It is positive and decreasing:
\[ \frac1{n+1}<\frac1n \]
And:
\[ \lim_{n\to\infty}\frac1n=0 \]
Therefore, by Leibniz's test:
\[ \boxed{\text{The alternating harmonic series converges.}} \]
Its sum is \(\log2\), which follows from a separate evaluation and is not required to establish convergence.
2.4.3 Absolute convergence
[DIRECTLY IN NOTES] Definition
A series
\[ \sum a_n \]
is absolutely convergent if
\[ \boxed{\sum |a_n|\text{ converges}} \]
Theorem
Every absolutely convergent series is convergent.
Proof outline [EXAM SUPPORT]
Since
\[ -|a_n|\le a_n\le |a_n| \]
the absolute-value convergence implies convergence of the positive and negative parts by comparison. Consequently, the original series converges.
2.4.4 Conditional convergence
A series is conditionally convergent if:
\[ \sum a_n \]
converges, but
\[ \sum|a_n| \]
diverges.
Example:
\[ 1-\frac12+\frac13-\frac14+\cdots \]
The alternating harmonic series converges by Leibniz's test.
But:
\[ 1+\frac12+\frac13+\frac14+\cdots \]
diverges.
Therefore the alternating harmonic series is conditionally convergent.
2.4.5 Absolute versus conditional convergence
Absolute convergence
Conditional convergence
\(\sum|a_n|\) converges
\(\sum|a_n|\) diverges
Original series converges
Original series converges
Rearrangement preserves the sum
Rearrangement may change the sum
Stronger property
Weaker property
2.4.6 Rearrangement of series
[EXAM SUPPORT] Riemann rearrangement theorem
For a conditionally convergent real series, there exists a rearrangement that converges to any prescribed real number. There are also rearrangements that diverge to \(+\infty\), to \(-\infty\), or fail to converge.
For an absolutely convergent series, every rearrangement has the same sum.
Exam rule
Absolute convergence: rearrangement does not change the sum.
Conditional convergence: rearrangement may change the sum.
⚠ Examiner’s flag: Rearranging terms is safe without changing the sum only when the series is absolutely convergent.

## Quick Convergence Test Reference Table

| Test Name | Convergence / Divergence Conditions & Results |
| :--- | :--- |
| **Term test** | If \(\lim a_n\ne0\) or fails to exist, series diverges |
| **Geometric** | Converges for \(|r|<1\) |
| **\(p\)-series** | Converges for \(p>1\); diverges for \(p\le1\) |
| **Direct comparison** | \(0\le a_n\le b_n\); convergence of \(b_n\) implies convergence of \(a_n\) |
| **Limit comparison** | \(0<\lim(a_n/b_n)<\infty\): same nature |
| **Ratio** | \(L<1\) converges, \(L>1\) diverges, \(L=1\) inconclusive |
| **Root** | \(L<1\) absolutely converges, \(L>1\) diverges, \(L=1\) inconclusive |
| **Raabe** | \(R>1\) converges, \(R<1\) diverges, \(R=1\) inconclusive |
| **Gauss** | \(\alpha>1\) converges, \(\alpha\le1\) diverges, with the stated expansion condition |
| **Logarithmic** | \(L>1\) converges, \(L<1\) diverges, \(L=1\) inconclusive |
| **Integral** | Positive continuous decreasing \(f\); series and improper integral share convergence |
| **Leibniz** | \(b_n\downarrow0\) gives alternating convergence |
| **Absolute** | \(\sum|a_n|\) converges |
| **Conditional** | \(\sum a_n\) converges but \(\sum|a_n|\) diverges |


# UNIT 3: ORDINARY DIFFERENTIAL EQUATIONS

Chapter 3.1: First-order differential equations
3.1.1 Definitions: differential equation, order and degree
[EXAM SUPPORT] Differential equation
An equation involving an unknown function and one or more of its derivatives is called a differential equation.
Ordinary differential equation (ODE): A differential equation involving an unknown function of one independent variable and its ordinary derivatives.
Partial differential equation (PDE): A differential equation involving partial derivatives with respect to two or more independent variables.
Order
The order of a differential equation is the order of the highest derivative present.
Degree
The degree is the power of the highest-order derivative after the equation has been made polynomial in its derivatives, free from radicals and fractional powers of derivatives.
Example:
\[ \left(\frac{d^2y}{dx^2}\right)^3 +2\frac{dy}{dx}+y=0 \]
Order = 2.
Degree = 3.
⚠ Examiner’s flag: Degree is not defined in the usual way if the differential equation cannot be expressed as a polynomial in its derivatives.
3.1.2 Exact differential equations
[DIRECTLY IN NOTES] Standard form
\[ M(x,y)\,dx+N(x,y)\,dy=0 \]
The equation is exact if there exists a function \(F(x,y)\) such that
\[ dF=F_x\,dx+F_y\,dy \]
and
\[ F_x=M,\qquad F_y=N \]
Exactness condition
If \(M\) and \(N\) have continuous first partial derivatives in a simply connected region, then the equation is exact if
\[ \boxed{ \frac{\partial M}{\partial y} = \frac{\partial N}{\partial x} } \]
Solution
For an exact equation:
\[ \boxed{F(x,y)=C} \]
where \(F\) satisfies
\[ F_x=M,\qquad F_y=N \]
Step-by-step algorithm
Write the differential equation in the form \(Mdx+Ndy=0\).
Identify \(M\) and \(N\).
Calculate \(M_y\).
Calculate \(N_x\).
If they are equal, the equation is exact.
Integrate \(M\) with respect to \(x\), treating \(y\) as constant.
Add an unknown function \(g(y)\).
Differentiate the resulting expression with respect to \(y\).
Compare with \(N\).
Determine \(g'(y)\), integrate and obtain \(F(x,y)=C\).
Solved numerical
Solve:
\[ (2xy+3)\,dx+(x^2+4y)\,dy=0 \]
Here:
\[ M=2xy+3 \]
\[ N=x^2+4y \]
Calculate:
\[ M_y=2x \]
\[ N_x=2x \]
Since:
\[ M_y=N_x \]
the equation is exact.
Integrate \(M\) with respect to \(x\):
\[ F=\int(2xy+3)\,dx \]
\[ F=x^2y+3x+g(y) \]
Differentiate with respect to \(y\):
\[ F_y=x^2+g'(y) \]
Compare with:
\[ N=x^2+4y \]
Thus:
\[ g'(y)=4y \]
\[ g(y)=2y^2 \]
Therefore:
\[ \boxed{x^2y+3x+2y^2=C} \]
3.1.3 Non-exact differential equations
[DIRECTLY IN NOTES]
An equation
\[ Mdx+Ndy=0 \]
is non-exact if
\[ \boxed{M_y\ne N_x} \]
An integrating factor may convert it into an exact equation.
If \(\mu(x,y)\) is an integrating factor, then
\[ \mu M\,dx+\mu N\,dy=0 \]
must satisfy
\[ \boxed{ \frac{\partial(\mu M)}{\partial y} = \frac{\partial(\mu N)}{\partial x} } \]
3.1.4 Integrating factor: general method
[DIRECTLY IN NOTES] Definition
An integrating factor is a non-zero function which, when multiplied throughout a differential equation, makes the equation exact or otherwise directly integrable.
Let:
\[ Mdx+Ndy=0 \]
After multiplication by \(\mu\):
\[ \mu Mdx+\mu Ndy=0 \]
The exactness condition becomes:
\[ \frac{\partial(\mu M)}{\partial y} = \frac{\partial(\mu N)}{\partial x} \]
3.1.5 Integrating factor Rule I
Standard rule [RESTORED STANDARD EQUATION]
If
\[ \frac{M_y-N_x}{N} \]
is a function of \(x\) alone, then an integrating factor is
\[ \boxed{ \mu(x)= e^{\int\frac{M_y-N_x}{N}\,dx} } \]
Algorithm
Identify \(M,N\).
Calculate \(M_y-N_x\).
Divide by \(N\).
Check whether the result depends on \(x\) alone.
Integrate with respect to \(x\).
Exponentiate to obtain \(\mu(x)\).
Multiply the original equation by \(\mu\).
Solve the resulting exact equation.
3.1.6 Integrating factor Rule II
Standard rule [RESTORED STANDARD EQUATION]
If
\[ \frac{N_x-M_y}{M} \]
is a function of \(y\) alone, then an integrating factor is
\[ \boxed{ \mu(y)= e^{\int\frac{N_x-M_y}{M}\,dy} } \]
Algorithm
Calculate \(N_x-M_y\).
Divide by \(M\).
Verify dependence on \(y\) alone.
Integrate with respect to \(y\).
Exponentiate.
Multiply the equation and solve.
⚠ Examiner’s flag: The numerator sign and denominator differ between Rule I and Rule II. Interchanging them changes the answer.
3.1.7 Integrating factor Rule III: homogeneous functions
[RESTORED STANDARD EQUATION]
If \(M(x,y)\) and \(N(x,y)\) are homogeneous functions of the same degree, then an integrating factor is
\[ \boxed{ \mu=\frac1{xM+yN} } \]
provided \(xM+yN\ne0\).
An equivalent expression, up to a non-zero constant factor, is sometimes written as
\[ \mu=\frac1{xM+yN} \]
Homogeneous function definition
A function \(f(x,y)\) is homogeneous of degree \(n\) if
\[ f(tx,ty)=t^nf(x,y) \]
for all admissible \(t\).
Algorithm
Check whether \(M\) and \(N\) have the same degree.
Form \(xM+yN\).
Use its reciprocal as the integrating factor.
Multiply the equation.
Verify exactness.
Integrate.
3.1.8 Integrating factor Rule IV: a function of \(xy\)
[RESTORED STANDARD EQUATION]
For
\[ Mdx+Ndy=0 \]
if
\[ \frac{1}{xM-yN} \left( \frac{\partial M}{\partial y} - \frac{\partial N}{\partial x} \right) \]
can be expressed as a function of \(xy\), say \(f(xy)\), an integrating factor depending on \(xy\) may be obtained from
\[ \boxed{ \mu(xy)= \exp\left(\int f(xy)\,d(xy)\right) } \]
This compact formula requires the specific derivative structure to reduce to a function of \(xy\). It should not be used merely because \(xy\) appears somewhere in the equation.
3.1.9 Integrating factor Rule V: special forms
[RESTORED STANDARD EQUATION]
Some textbooks present additional integrating-factor rules for special forms such as
\[ Mdx+Ndy=0 \]
where a particular ratio involving \(M,N\) and their partial derivatives is a function of a linear combination such as \(ax+by\), or where the equation has a reducible homogeneous structure.
Because the CU repository's extracted lecture text identifies Rules III, IV and V but does not preserve all slide formulas clearly, the exact fifth rule cannot be certified from the extracted text alone.
A reliable general approach is to solve the exactness equation for \(\mu\):
\[ \boxed{ \mu_yM+\mu M_y = \mu_xN+\mu N_x } \]
This is a first-order PDE for the integrating factor.
Exam preparation instruction: Use the precise Rule III, IV and V forms in the faculty's original slide image if they were provided there. Do not substitute an unverified variant from another textbook and label it as the faculty's rule.
3.1.10 Worked non-exact equation using Rule I
Solve:
\[ y\,dx+2x\,dy=0 \]
Here:
\[ M=y,\qquad N=2x \]
\[ M_y=1,\qquad N_x=2 \]
Calculate:
\[ \frac{M_y-N_x}{N} = \frac{1-2}{2x} = -\frac1{2x} \]
This is a function of \(x\) alone.
Therefore:
\[ \mu(x)=e^{\int-\frac1{2x}\,dx} \]
\[ \mu(x)=e^{-\frac12\log|x|} \]
\[ \mu(x)=\frac1{\sqrt{|x|}} \]
On a domain \(x>0\), use
\[ \mu=x^{-1/2} \]
Multiply:
\[ \frac{y}{\sqrt{x}}dx+2\sqrt{x}\,dy=0 \]
This is exact because
\[ \frac{\partial}{\partial y} \left(\frac{y}{\sqrt{x}}\right)=\frac1{\sqrt{x}} \]
and
\[ \frac{\partial}{\partial x}(2\sqrt{x}) =\frac1{\sqrt{x}} \]
Integrate the first component:
\[ F=\int\frac{y}{\sqrt{x}}\,dx \]
\[ F=2y\sqrt{x}+g(y) \]
Differentiate with respect to \(y\):
\[ F_y=2\sqrt{x}+g'(y) \]
Compare with \(2\sqrt{x}\):
\[ g'(y)=0 \]
Hence:
\[ \boxed{2y\sqrt{x}=C} \]
3.1.11 Leibniz linear differential equation
The repository uses the heading “Leibnitz LDE.” The standard form is the first-order linear differential equation.
[DIRECTLY IN NOTES] Standard form
\[ \boxed{ \frac{dy}{dx}+P(x)y=Q(x) } \]
Integrating factor
\[ \boxed{ IF=e^{\int P(x)\,dx} } \]
General solution
Multiply throughout by the integrating factor:
\[ IF\frac{dy}{dx}+IF\cdot Py=IF\cdot Q \]
The left-hand side becomes a product derivative:
\[ \frac{d}{dx}(y\cdot IF)=Q\cdot IF \]
Integrate:
\[ y\cdot IF=\int Q\cdot IF\,dx+C \]
Therefore:
\[ \boxed{ y=\frac{1}{IF} \left[\int Q\cdot IF\,dx+C\right] } \]
Algorithm
Rearrange the equation into \(y'+Py=Q\).
Identify \(P(x)\) and \(Q(x)\).
Compute \(IF=e^{\int Pdx}\).
Multiply the complete equation by \(IF\).
Convert the left side into \(\frac{d}{dx}(yIF)\).
Integrate.
Divide by \(IF\).
Include the arbitrary constant.
Solved numerical
Solve:
\[ \frac{dy}{dx}+2y=e^{-x} \]
Here:
\[ P=2,\qquad Q=e^{-x} \]
Integrating factor:
\[ IF=e^{\int2dx}=e^{2x} \]
Multiply throughout:
\[ e^{2x}\frac{dy}{dx}+2e^{2x}y=e^x \]
Thus:
\[ \frac{d}{dx}(ye^{2x})=e^x \]
Integrate:
\[ ye^{2x}=e^x+C \]
Therefore:
\[ \boxed{y=e^{-x}+Ce^{-2x}} \]
3.1.12 Bernoulli's differential equation
[EXAM SUPPORT] Standard form
\[ \boxed{ \frac{dy}{dx}+Py=Qy^n } \]
where \(n\ne0,1\) for the nonlinear Bernoulli case.
Substitution
Divide by \(y^n\):
\[ y^{-n}\frac{dy}{dx}+Py^{1-n}=Q \]
Let:
\[ \boxed{v=y^{1-n}} \]
Then:
\[ \frac{dv}{dx}=(1-n)y^{-n}\frac{dy}{dx} \]
So:
\[ y^{-n}\frac{dy}{dx} =\frac1{1-n}\frac{dv}{dx} \]
Multiply by \(1-n\):
\[ \frac{dv}{dx}+(1-n)Pv=(1-n)Q \]
This is linear in \(v\).
Algorithm
Identify \(P,Q,n\).
Divide by \(y^n\).
Substitute \(v=y^{1-n}\).
Differentiate to obtain \(v'\).
Convert to a first-order linear equation.
Find the integrating factor.
Solve for \(v\).
Substitute back to find \(y\).
Solved numerical
Solve:
\[ \frac{dy}{dx}+y=xy^2 \]
Here:
\[ P=1,\quad Q=x,\quad n=2 \]
Divide by \(y^2\):
\[ y^{-2}\frac{dy}{dx}+y^{-1}=x \]
Let:
\[ v=y^{-1} \]
Then:
\[ \frac{dv}{dx}=-y^{-2}\frac{dy}{dx} \]
Therefore:
\[ -\frac{dv}{dx}+v=x \]
or
\[ \frac{dv}{dx}-v=-x \]
This is linear.
Integrating factor:
\[ IF=e^{\int-1dx}=e^{-x} \]
Multiply:
\[ e^{-x}v'-e^{-x}v=-xe^{-x} \]
\[ \frac{d}{dx}(ve^{-x})=-xe^{-x} \]
Integrate by parts:
\[ ve^{-x}=(x+1)e^{-x}+C \]
Multiply by \(e^x\):
\[ v=x+1+Ce^x \]
Since \(v=1/y\):
\[ \boxed{ y=\frac1{x+1+Ce^x} } \]
Chapter 3.2: Higher-order linear differential equations with constant coefficients
3.2.1 Linear differential equation with constant coefficients
[DIRECTLY IN NOTES] Definition
A linear differential equation with constant coefficients has the form
\[ \boxed{ a_n\frac{d^ny}{dx^n} +a_{n-1}\frac{d^{n-1}y}{dx^{n-1}} +\cdots+a_1\frac{dy}{dx}+a_0y=X(x) } \]
where \(a_i\) are constants and \(X(x)\) is a known function.
Introduce the differential operator:
\[ D=\frac{d}{dx} \]
Then:
\[ \boxed{ f(D)y=X(x) } \]
where
\[ f(D)=a_nD^n+a_{n-1}D^{n-1}+\cdots+a_1D+a_0 \]
3.2.2 General solution
The complete solution is
\[ \boxed{y=CF+PI} \]
where:
\(CF\) is the complementary function.
\(PI\) is the particular integral.
The CF solves the homogeneous equation:
\[ f(D)y=0 \]
The PI is one solution of the non-homogeneous equation:
\[ f(D)y=X(x) \]
3.2.3 Auxiliary equation
To find the complementary function, replace \(D\) by \(m\):
\[ \boxed{f(m)=0} \]
This is the auxiliary or characteristic equation.
For a second-order equation:
\[ aD^2+bD+c=0 \]
the auxiliary equation is:
\[ am^2+bm+c=0 \]
3.2.4 Case 1: Real and distinct roots
If the roots are distinct real values \(m_1,m_2\), then
\[ \boxed{CF=C_1e^{m_1x}+C_2e^{m_2x}} \]
For \(n\) distinct real roots:
\[ CF=C_1e^{m_1x}+\cdots+C_ne^{m_nx} \]
3.2.5 Case 2: Real repeated roots
If \(m\) is a repeated root of multiplicity \(r\), then the corresponding CF part is
\[ \boxed{ e^{mx} (C_1+C_2x+\cdots+C_rx^{r-1}) } \]
For a repeated root of multiplicity 2:
\[ CF=(C_1+C_2x)e^{mx} \]
For a repeated root of multiplicity 3:
\[ CF=(C_1+C_2x+C_3x^2)e^{mx} \]
3.2.6 Case 3: Imaginary or complex conjugate roots
If the roots are
\[ m=\alpha\pm i\beta \]
then the corresponding real-valued complementary function is
\[ \boxed{ CF=e^{\alpha x} (C_1\cos\beta x+C_2\sin\beta x) } \]
For purely imaginary roots:
\[ m=\pm i\beta \]
\[ \boxed{ CF=C_1\cos\beta x+C_2\sin\beta x } \]
3.2.7 Solved numerical: distinct roots
Solve:
\[ y''-5y'+6y=0 \]
Auxiliary equation:
\[ m^2-5m+6=0 \]
Factor:
\[ (m-2)(m-3)=0 \]
Roots:
\[ m_1=2,\quad m_2=3 \]
Therefore:
\[ \boxed{y=C_1e^{2x}+C_2e^{3x}} \]
3.2.8 Solved numerical: repeated roots
Solve:
\[ y''-4y'+4y=0 \]
Auxiliary equation:
\[ m^2-4m+4=0 \]
\[ (m-2)^2=0 \]
Repeated root:
\[ m=2 \]
Therefore:
\[ \boxed{y=(C_1+C_2x)e^{2x}} \]
3.2.9 Solved numerical: imaginary roots
Solve:
\[ y''+9y=0 \]
Auxiliary equation:
\[ m^2+9=0 \]
\[ m=\pm3i \]
Therefore:
\[ \boxed{y=C_1\cos3x+C_2\sin3x} \]
Chapter 3.3: Particular integral methods
3.3.1 Particular integral in operator form
[DIRECTLY IN NOTES]
For a linear differential equation with constant coefficients:
\[ f(D)y=X \]
the particular integral is written as
\[ \boxed{ PI=\frac1{f(D)}X } \]
Therefore:
\[ \boxed{ y=CF+\frac1{f(D)}X } \]
The operator \(D\) represents differentiation with respect to \(x\).
3.3.2 Rule for \(X=e^{ax}\)
[RESTORED STANDARD EQUATION]
If
\[ f(a)\ne0 \]
then
\[ \boxed{ \frac1{f(D)}e^{ax} =\frac{e^{ax}}{f(a)} } \]
Algorithm
Identify \(f(D)\).
Replace \(D\) by \(a\) to obtain \(f(a)\).
Check \(f(a)\ne0\).
Divide \(e^{ax}\) by \(f(a)\).
Example
Find PI for:
\[ (D^2-5D+6)y=e^{2x} \]
Here:
\[ f(D)=D^2-5D+6 \]
\[ f(2)=4-10+6=0 \]
The direct exponential rule fails because \(f(2)=0\).
Factor:
\[ f(D)=(D-2)(D-3) \]
Since \(e^{2x}\) corresponds to a root \(2\), use the repeated-root/failure case.
Failure rule
If \(f(a)=0\) and \(a\) is a simple root, then
\[ \boxed{ PI=\frac{x e^{ax}}{f'(a)} } \]
Here:
\[ f'(D)=2D-5 \]
\[ f'(2)=4-5=-1 \]
Therefore:
\[ \boxed{PI=-xe^{2x}} \]
If \(a\) is a root of multiplicity \(r\), then
\[ \boxed{ PI= \frac{x^r e^{ax}}{r!\,g(a)} } \]
where
\[ f(D)=(D-a)^r g(D),\qquad g(a)\ne0 \]
3.3.3 Rule for \(\sin ax\) and \(\cos ax\)
[RESTORED STANDARD EQUATION]
For a polynomial operator \(f(D)\):
\[ \boxed{ \frac1{f(D)}\sin ax = \operatorname{Im}\left(\frac{e^{iax}}{f(ia)}\right) } \]
\[ \boxed{ \frac1{f(D)}\cos ax = \operatorname{Re}\left(\frac{e^{iax}}{f(ia)}\right) } \]
provided \(f(ia)\ne0\).
If
\[ f(ia)=A+iB \]
then rationalize:
\[ \frac1{A+iB}=\frac{A-iB}{A^2+B^2} \]
Example
Find PI:
\[ (D^2+4)y=\sin2x \]
Calculate:
\[ f(D)=D^2+4 \]
\[ f(2i)=(2i)^2+4=-4+4=0 \]
The ordinary rule fails. Since the operator has a resonance with the input frequency, use the failure rule or solve by a suitable trial function.
Assume:
\[ y_p=Ax\cos2x \]
Differentiate:
\[ y_p'=A\cos2x-2Ax\sin2x \]
\[ y_p''=-4A\sin2x-4Ax\cos2x \]
Then:
\[ y_p''+4y_p=-4A\sin2x \]
Equate to \(\sin2x\):
\[ -4A=1 \]
\[ A=-\frac14 \]
Thus:
\[ \boxed{PI=-\frac{x}{4}\cos2x} \]
3.3.4 Rule for polynomial forcing \(X=x^m\)
[RESTORED STANDARD EQUATION]
If \(f(0)\ne0\), expand \(1/f(D)\) as a series in powers of \(D\), truncating after the \(m\)-th derivative because higher derivatives of \(x^m\) vanish.
\[ \boxed{ PI=\frac1{f(D)}x^m } \]
Example
Find PI:
\[ (D^2-3D+2)y=x^2 \]
Here:
\[ f(D)=D^2-3D+2 \]
Factor:
\[ f(D)=(D-1)(D-2) \]
Expand about \(D=0\):
\[ \frac1{D^2-3D+2} = \frac1{2} \frac1{1-\frac32D+\frac12D^2} \]
For this example, it is convenient to assume:
\[ y_p=Ax^2+Bx+C \]
Then:
\[ y_p'=2Ax+B \]
\[ y_p''=2A \]
Substitute:
\[ 2A-3(2Ax+B)+2(Ax^2+Bx+C)=x^2 \]
\[ 2Ax^2+(-6A+2B)x+(2A-3B+2C)=x^2 \]
Compare coefficients:
\[ 2A=1\implies A=\frac12 \]
\[ -6A+2B=0 \implies B=\frac32 \]
\[ 2A-3B+2C=0 \]
\[ 1-\frac92+2C=0 \]
\[ C=\frac74 \]
Therefore:
\[ \boxed{ PI=\frac{x^2}{2}+\frac{3x}{2}+\frac74 } \]
3.3.5 Rule for \(e^{ax}V(x)\)
[RESTORED STANDARD EQUATION] Exponential shift rule
\[ \boxed{ \frac1{f(D)}e^{ax}V(x) = e^{ax}\frac1{f(D+a)}V(x) } \]
This follows from:
\[ D(e^{ax}V)=e^{ax}(D+a)V \]
Algorithm
Identify the exponential factor \(e^{ax}\).
Move it outside.
Replace each \(D\) in the operator by \(D+a\).
Apply the remaining operator to \(V(x)\).
3.3.6 Rule for \(xV(x)\)
[RESTORED STANDARD EQUATION]
Using the operator identity
\[ f(D)x=xf(D)+f'(D) \]
a useful inverse-operator form is
\[ \boxed{ \frac1{f(D)}xV = \left[ x-\frac{f'(D)}{f(D)} \right]\frac1{f(D)}V } \]
provided the operator inverses involved are meaningful.
Algorithm
Calculate \(f'(D)\), the derivative of \(f\) with respect to its operator argument.
Find \(f(D)^{-1}V\).
Apply the \(x\)-operator identity.
Simplify.
3.3.7 Failure rules for particular integrals
The standard shortcuts need modification when the input exponential or sinusoidal term corresponds to a root of the auxiliary polynomial.
Exponential failure
If
\[ f(a)=0 \]
and \(a\) is a simple root:
\[ PI=\frac{x e^{ax}}{f'(a)} \]
Repeated exponential root
If \(a\) has multiplicity \(r\):
\[ f(D)=(D-a)^rg(D) \]
with \(g(a)\ne0\), then
\[ PI=\frac{x^re^{ax}}{r!g(a)} \]
Trigonometric failure
If the characteristic polynomial vanishes at \(ia\), the basic trigonometric shortcut fails. Use a trial function multiplied by \(x\), or apply the complex exponential resonance rule.
For a simple pair of roots \(\pm ia\), one standard rule is to multiply the ordinary trial expression by \(x\).
⚠ Examiner’s flag: Never use \(e^{ax}/f(a)\) when \(f(a)=0\). That would involve division by zero.
Chapter 3.4: Method of variation of parameters
3.4.1 Definition
[DIRECTLY IN NOTES]
Variation of parameters is a method for finding a particular integral of a non-homogeneous linear differential equation by replacing the constants in the complementary function with functions of the independent variable.
For the second-order equation:
\[ \boxed{ y''+P(x)y'+Q(x)y=R(x) } \]
Let the complementary function be
\[ CF=C_1y_1+C_2y_2 \]
where \(y_1,y_2\) are linearly independent solutions of the homogeneous equation.
Assume a particular solution:
\[ y_p=u(x)y_1+v(x)y_2 \]
3.4.2 Wronskian
Definition [RESTORED STANDARD EQUATION]
The Wronskian of \(y_1,y_2\) is
\[ \boxed{ W(y_1,y_2)= \begin{vmatrix} y_1&y_2\\ y_1'&y_2' \end{vmatrix} } \]
Thus:
\[ W=y_1y_2'-y_2y_1' \]
If \(W(x)\ne0\) at a point, the solutions are linearly independent on the relevant interval.
3.4.3 Variation of parameters formulas
For
\[ y''+Py'+Qy=R \]
the parameter functions satisfy:
\[ \boxed{ u'=-\frac{y_2R}{W} } \]
\[ \boxed{ v'=\frac{y_1R}{W} } \]
Therefore:
\[ \boxed{ u=-\int\frac{y_2R}{W}\,dx } \]
\[ \boxed{ v=\int\frac{y_1R}{W}\,dx } \]
The particular integral is
\[ \boxed{ PI=uy_1+vy_2 } \]
Hence:
\[ \boxed{ y=C_1y_1+C_2y_2+uy_1+vy_2 } \]
Conditions
The equation must be linear.
The coefficient of \(y''\) must be 1 for the stated formulas.
\(y_1,y_2\) must be independent solutions of the homogeneous equation.
The Wronskian must be non-zero on the solution interval.
If the original equation is
\[ a(x)y''+b(x)y'+c(x)y=r(x) \]
first divide by \(a(x)\), assuming \(a(x)\ne0\).
3.4.4 Derivation outline
Assume:
\[ y_p=uy_1+vy_2 \]
Impose the auxiliary condition:
\[ u'y_1+v'y_2=0 \]
Then:
\[ y_p'=uy_1'+vy_2' \]
Differentiating:
\[ y_p''=u'y_1'+uy_1''+v'y_2'+vy_2'' \]
Substitute into the differential equation. Because \(y_1,y_2\) satisfy the homogeneous equation, the terms involving \(u,v\) cancel. This gives:
\[ u'y_1'+v'y_2'=R \]
Together:
\[ u'y_1+v'y_2=0 \]
\[ u'y_1'+v'y_2'=R \]
Solving the two equations:
\[ u'=-\frac{y_2R}{W} \]
\[ v'=\frac{y_1R}{W} \]
3.4.5 Solved numerical
Solve:
\[ y''+y=\sec x \]
Step 1: Homogeneous equation
\[ y''+y=0 \]
Auxiliary equation:
\[ m^2+1=0 \]
\[ m=\pm i \]
Thus:
\[ y_1=\cos x,\quad y_2=\sin x \]
\[ CF=C_1\cos x+C_2\sin x \]
Step 2: Wronskian
\[ W= \begin{vmatrix} \cos x&\sin x\\ -\sin x&\cos x \end{vmatrix} \]
\[ W=\cos^2x+\sin^2x \]
\[ \boxed{W=1} \]
Step 3: Find \(u\)
Here:
\[ R=\sec x \]
\[ u=-\int\frac{y_2R}{W}\,dx \]
\[ u=-\int\sin x\sec x\,dx \]
\[ u=-\int\tan x\,dx \]
\[ \boxed{u=\log|\cos x|} \]
Step 4: Find \(v\)
\[ v=\int\frac{y_1R}{W}\,dx \]
\[ v=\int\cos x\sec x\,dx \]
\[ v=\int1\,dx \]
\[ \boxed{v=x} \]
Step 5: Particular integral
\[ PI=u\cos x+v\sin x \]
\[ \boxed{PI=\cos x\log|\cos x|+x\sin x} \]
Complete solution
\[ \boxed{ y=C_1\cos x+C_2\sin x +\cos x\log|\cos x|+x\sin x } \]
This solution is valid on intervals where \(\cos x\ne0\).
Chapter 3.5: Cauchy's homogeneous and Legendre's linear differential equations
3.5.1 Cauchy-Euler or Cauchy's homogeneous equation
[DIRECTLY IN NOTES] Definition
A Cauchy-Euler equation is a linear differential equation in which the coefficient of each derivative is a power of \(x\) matching the order of that derivative.
The general form is:
\[ \boxed{ a_nx^ny^{(n)} +a_{n-1}x^{n-1}y^{(n-1)} +\cdots+a_1xy'+a_0y=X(x) } \]
For a second-order homogeneous equation:
\[ \boxed{ ax^2y''+bxy'+cy=0 } \]
3.5.2 Method 1: Trial solution
Assume:
\[ \boxed{y=x^m} \]
Then:
\[ y'=mx^{m-1} \]
\[ y''=m(m-1)x^{m-2} \]
Substitute:
\[ ax^2m(m-1)x^{m-2} +bxmx^{m-1} +cx^m=0 \]
Factor \(x^m\):
\[ x^m[am(m-1)+bm+c]=0 \]
The auxiliary equation is:
\[ \boxed{ am(m-1)+bm+c=0 } \]
Root cases
- Distinct real \(m_1,m_2\):
\[ y=C_1x^{m_1}+C_2x^{m_2} \]
- Repeated real root \(m\):
\[ y=x^m(C_1+C_2\log x) \]
- Complex roots \(\alpha\pm i\beta\):
\[ y=x^\alpha [C_1\cos(\beta\log x)+C_2\sin(\beta\log x)] \]
For \(x<0\), the formulas are normally expressed using \(\log|x|\) on an interval that does not cross zero.
3.5.3 Method 2: Substitution \(x=e^z\)
[DIRECTLY IN NOTES as a transformation]
Let:
\[ \boxed{x=e^z} \]
Then:
\[ z=\log x \]
Using the chain rule:
\[ \frac{dy}{dx}=\frac1x\frac{dy}{dz} \]
Thus:
\[ xy'=D_1y \]
where
\[ D_1=\frac{d}{dz} \]
For the second derivative:
\[ x^2y''=D_1(D_1-1)y \]
More generally:
\[ \boxed{ x^ny^{(n)} = D_1(D_1-1)\cdots(D_1-n+1)y } \]
The transformed differential equation has constant coefficients in \(z\).
Example
Solve:
\[ x^2y''-3xy'+4y=0 \]
With \(x=e^z\):
\[ x^2y''=D_1(D_1-1)y \]
\[ xy'=D_1y \]
Therefore:
\[ [D_1(D_1-1)-3D_1+4]y=0 \]
\[ (D_1^2-4D_1+4)y=0 \]
\[ (D_1-2)^2y=0 \]
Thus:
\[ y=(C_1+C_2z)e^{2z} \]
Since \(z=\log x\) and \(e^{2z}=x^2\):
\[ \boxed{ y=x^2(C_1+C_2\log x) } \]
3.5.4 Legendre's linear differential equation
[DIRECTLY IN NOTES]
A Legendre-type linear equation commonly takes the form:
\[ \boxed{ (ax+b)^ny^{(n)} +\cdots = X(x) } \]
For the second-order form:
\[ \boxed{ (ax+b)^2y''+A(ax+b)y'+By=X(x) } \]
A standard substitution is:
\[ \boxed{ax+b=e^z} \]
Let:
\[ z=\log(ax+b) \]
Then:
\[ \frac{dz}{dx}=\frac{a}{ax+b} \]
So:
\[ \frac{dy}{dx}=\frac{a}{ax+b}D_1y \]
Therefore:
\[ (ax+b)y'=aD_1y \]
And:
\[ (ax+b)^2y''=a^2D_1(D_1-1)y \]
After substitution, the equation becomes a constant-coefficient differential equation in \(z\).
Working algorithm
Identify the repeated linear coefficient \(ax+b\).
Put \(ax+b=e^z\).
Express derivatives in terms of \(D_1=d/dz\).
Substitute into the original equation.
Obtain a constant-coefficient equation.
Solve for \(y(z)\).
Replace \(z\) by \(\log(ax+b)\).
Example
Solve:
\[ (ax+b)^2y''+2(ax+b)y'+y=0 \]
Using:
\[ (ax+b)^2y''=a^2D_1(D_1-1)y \]
\[ (ax+b)y'=aD_1y \]
The equation becomes:
\[ [a^2D_1(D_1-1)+2aD_1+1]y=0 \]
\[ [a^2D_1^2+(2a-a^2)D_1+1]y=0 \]
Solve the auxiliary equation in \(D_1\), then substitute back \(z=\log(ax+b)\).
⚠ Examiner’s flag: The exact coefficient pattern of the Legendre equation must be read from the problem. Do not assume every equation containing \(ax+b\) has the same coefficients. The substitution transforms a particular variable-coefficient structure; it does not remove arbitrary variable coefficients.

# HIGH-YIELD CLOSING SECTION A: 15 SOLVED EXAM-STANDARD NUMERICALS

These problems are representative practice problems constructed from the course topics. They are not claimed to be extracted verbatim from previous CU examination papers.
Unit 1: Matrices and linear algebra

### Numerical 1: Rank of a matrix

Find the rank of:
\[ A= \begin{bmatrix} 1&2&3\\ 2&4&6\\ 1&3&4 \end{bmatrix} \]
Apply:
\[ R_2\rightarrow R_2-2R_1 \]
\[ R_3\rightarrow R_3-R_1 \]
\[ A\sim \begin{bmatrix} 1&2&3\\ 0&0&0\\ 0&1&1 \end{bmatrix} \]
Interchange rows 2 and 3:
\[ A\sim \begin{bmatrix} 1&2&3\\ 0&1&1\\ 0&0&0 \end{bmatrix} \]
There are two non-zero rows.
\[ \boxed{\operatorname{rank}(A)=2} \]

### Numerical 2: Consistency using Rouché-Capelli theorem

Examine:
\[ x+y+z=6 \]
\[ 2x-y+z=3 \]
\[ 3x+2y+2z=9 \]
Augmented matrix:
\[ \left[ \begin{array}{ccc|c} 1&1&1&6\\ 2&-1&1&3\\ 3&2&2&9 \end{array} \right] \]
Apply:
\[ R_2\rightarrow R_2-2R_1 \]
\[ R_3\rightarrow R_3-3R_1 \]
\[ \left[ \begin{array}{ccc|c} 1&1&1&6\\ 0&-3&-1&-9\\ 0&-1&-1&-9 \end{array} \right] \]
Apply:
\[ R_3\rightarrow3R_3-R_2 \]
\[ \left[ \begin{array}{ccc|c} 1&1&1&6\\ 0&-3&-1&-9\\ 0&0&-2&-18 \end{array} \right] \]
All three coefficient pivots are non-zero.
Thus:
\[ r=r'=3=n \]
Therefore a unique solution exists.
Back-substitution:
\[ -2z=-18\implies z=9 \]
\[ -3y-z=-9 \]
\[ -3y-9=-9\implies y=0 \]
\[ x+y+z=6 \]
\[ x+9=6\implies x=-3 \]
\[ \boxed{x=-3,\quad y=0,\quad z=9} \]

### Numerical 3: Eigenvalues and eigenvectors

Find eigenvalues and eigenvectors of:
\[ A= \begin{bmatrix} 2&1\\ 1&2 \end{bmatrix} \]
Characteristic equation:
\[ |A-\lambda I|=0 \]
\[ \begin{vmatrix} 2-\lambda&1\\ 1&2-\lambda \end{vmatrix}=0 \]
\[ (2-\lambda)^2-1=0 \]
\[ \lambda^2-4\lambda+3=0 \]
\[ (\lambda-1)(\lambda-3)=0 \]
Thus:
\[ \boxed{\lambda_1=3,\quad\lambda_2=1} \]
For \(\lambda=3\):
\[ A-3I= \begin{bmatrix} -1&1\\ 1&-1 \end{bmatrix} \]
Hence:
\[ -x+y=0 \]
Choose \(x=1,y=1\):
\[ \boxed{X_1=\begin{bmatrix}1\\1\end{bmatrix}} \]
For \(\lambda=1\):
\[ A-I= \begin{bmatrix} 1&1\\ 1&1 \end{bmatrix} \]
Thus:
\[ x+y=0 \]
Choose \(x=1,y=-1\):
\[ \boxed{X_2=\begin{bmatrix}1\\-1\end{bmatrix}} \]
Check trace:
\[ \operatorname{tr}(A)=2+2=4=3+1 \]
Check determinant:
\[ |A|=4-1=3=3(1) \]

### Numerical 4: Cayley-Hamilton inverse

Find the inverse of:
\[ A= \begin{bmatrix} 2&1\\ 1&1 \end{bmatrix} \]
Characteristic equation:
\[ |A-\lambda I|=0 \]
\[ \begin{vmatrix} 2-\lambda&1\\ 1&1-\lambda \end{vmatrix}=0 \]
\[ (2-\lambda)(1-\lambda)-1=0 \]
\[ \lambda^2-3\lambda+1=0 \]
By Cayley-Hamilton:
\[ A^2-3A+I=O \]
Multiply by \(A^{-1}\):
\[ A-3I+A^{-1}=O \]
Therefore:
\[ A^{-1}=3I-A \]
\[ A^{-1}= \begin{bmatrix} 3&0\\ 0&3 \end{bmatrix} - \begin{bmatrix} 2&1\\ 1&1 \end{bmatrix} \]
\[ \boxed{ A^{-1}= \begin{bmatrix} 1&-1\\ -1&2 \end{bmatrix} } \]
Unit 2: Sequences and infinite series

### Numerical 5: Geometric series

Find the sum:
\[ 8+4+2+1+\cdots \]
Here:
\[ a=8,\quad r=\frac12 \]
Since:
\[ |r|<1 \]
the series converges.
\[ S=\frac{a}{1-r} \]
\[ S=\frac8{1-\frac12} \]
\[ \boxed{S=16} \]

### Numerical 6: Direct comparison test

Test:
\[ \sum_{n=1}^{\infty}\frac1{n^2+5} \]
Since:
\[ 0<\frac1{n^2+5}<\frac1{n^2} \]
and
\[ \sum_{n=1}^{\infty}\frac1{n^2} \]
is a convergent \(p\)-series because \(p=2>1\), the given series converges by comparison.
\[ \boxed{\text{Convergent}} \]

### Numerical 7: Ratio test

Test:
\[ \sum_{n=1}^{\infty}\frac{2^n}{n!} \]
Let:
\[ a_n=\frac{2^n}{n!} \]
Then:
\[ a_{n+1}=\frac{2^{n+1}}{(n+1)!} \]
Calculate:
\[ \frac{a_{n+1}}{a_n} = \frac{2^{n+1}}{(n+1)!} \cdot\frac{n!}{2^n} \]
\[ =\frac2{n+1} \]
Taking limit:
\[ L=\lim_{n\to\infty}\frac2{n+1}=0 \]
Since \(L<1\):
\[ \boxed{\text{The series converges.}} \]

### Numerical 8: Raabe's test

Test:
\[ \sum_{n=1}^{\infty}\frac1{n^3} \]
Let:
\[ a_n=\frac1{n^3} \]
\[ \frac{a_n}{a_{n+1}} =\left(\frac{n+1}{n}\right)^3 \]
\[ R=\lim_{n\to\infty} n\left[ \left(1+\frac1n\right)^3-1 \right] \]
Expand:
\[ \left(1+\frac1n\right)^3 = 1+\frac3n+\frac3{n^2}+\frac1{n^3} \]
Therefore:
\[ R=\lim_{n\to\infty} \left(3+\frac3n+\frac1{n^2}\right) \]
\[ \boxed{R=3>1} \]
Thus the series converges.

### Numerical 9: Integral test

Test:
\[ \sum_{n=2}^{\infty}\frac1{n\log n} \]
Let:
\[ f(x)=\frac1{x\log x} \]
It is positive, continuous and decreasing for \(x\ge2\).
Evaluate:
\[ \int_2^\infty\frac{dx}{x\log x} \]
Put:
\[ u=\log x \]
\[ du=\frac{dx}{x} \]
Then:
\[ \int_{\log2}^{\infty}\frac{du}{u} \]
\[ =\lim_{b\to\infty} [\log u]_{\log2}^{b} \]
This tends to infinity.
Therefore:
\[ \boxed{\text{The series diverges.}} \]

### Numerical 10: Leibniz's test and absolute convergence

Test:
\[ 1-\frac13+\frac15-\frac17+\cdots \]
Write:
\[ \sum_{n=0}^{\infty}\frac{(-1)^n}{2n+1} \]
Let:
\[ b_n=\frac1{2n+1} \]
It is positive, decreasing, and:
\[ \lim_{n\to\infty}b_n=0 \]
Therefore it converges by Leibniz's test.
For absolute convergence:
\[ \sum_{n=0}^{\infty}\frac1{2n+1} \]
This is comparable to the harmonic series and diverges.
Thus:
\[ \boxed{\text{The original series is conditionally convergent.}} \]

## Common Mistakes: Unit 3: Differential equations


### Numerical 11: Exact differential equation

Solve:
\[ (3x^2+2y)\,dx+(2x+4y)\,dy=0 \]
Here:
\[ M=3x^2+2y \]
\[ N=2x+4y \]
\[ M_y=2,\qquad N_x=2 \]
The equation is exact.
Integrate \(M\) with respect to \(x\):
\[ F=\int(3x^2+2y)\,dx \]
\[ F=x^3+2xy+g(y) \]
Differentiate:
\[ F_y=2x+g'(y) \]
Compare with \(N\):
\[ 2x+g'(y)=2x+4y \]
\[ g'(y)=4y \]
\[ g(y)=2y^2 \]
Thus:
\[ \boxed{x^3+2xy+2y^2=C} \]

### Numerical 12: Linear differential equation

Solve:
\[ \frac{dy}{dx}+3y=6 \]
Here:
\[ P=3,\quad Q=6 \]
\[ IF=e^{\int3dx}=e^{3x} \]
Multiply:
\[ e^{3x}y'+3e^{3x}y=6e^{3x} \]
\[ \frac{d}{dx}(ye^{3x})=6e^{3x} \]
Integrate:
\[ ye^{3x}=2e^{3x}+C \]
\[ \boxed{y=2+Ce^{-3x}} \]

### Numerical 13: Bernoulli differential equation

Solve:
\[ \frac{dy}{dx}-y=y^2 \]
Here:
\[ P=-1,\quad Q=1,\quad n=2 \]
Divide by \(y^2\):
\[ y^{-2}y'-y^{-1}=1 \]
Put:
\[ v=y^{-1} \]
Then:
\[ v'=-y^{-2}y' \]
So:
\[ -v'-v=1 \]
\[ v'+v=-1 \]
The integrating factor is:
\[ IF=e^{\int1dx}=e^x \]
Multiply:
\[ \frac{d}{dx}(ve^x)=-e^x \]
Integrate:
\[ ve^x=-e^x+C \]
\[ v=-1+Ce^{-x} \]
Since \(v=1/y\):
\[ \boxed{y=\frac1{Ce^{-x}-1}} \]
The solution \(y=0\), which was excluded when dividing by \(y^2\), must also be considered separately.

### Numerical 14: Higher-order constant-coefficient equation

Solve:
\[ y''-2y'+5y=0 \]
Auxiliary equation:
\[ m^2-2m+5=0 \]
\[ m=\frac{2\pm\sqrt{4-20}}2 \]
\[ m=1\pm2i \]
Therefore:
\[ \boxed{ y=e^x(C_1\cos2x+C_2\sin2x) } \]

### Numerical 15: Cauchy-Euler equation

Solve:
\[ x^2y''-2xy'+2y=0 \]
Assume:
\[ y=x^m \]
Then:
\[ y'=mx^{m-1} \]
\[ y''=m(m-1)x^{m-2} \]
Substitute:
\[ x^2m(m-1)x^{m-2} -2xmx^{m-1}+2x^m=0 \]
\[ x^m[m(m-1)-2m+2]=0 \]
Auxiliary equation:
\[ m^2-3m+2=0 \]
\[ (m-1)(m-2)=0 \]
Thus:
\[ m_1=1,\quad m_2=2 \]
\[ \boxed{y=C_1x+C_2x^2} \]

# HIGH-YIELD CLOSING SECTION B: COMMON MISTAKES TO AVOID IN THE EXAM


## Common Mistakes: Unit 1: Matrices

Do not confuse matrix order \(m\times n\) with \(n\times m\).
Do not claim a rectangular matrix has a determinant.
Do not multiply a row by zero during elementary row reduction.
Do not count zero rows when calculating rank.
Do not confuse REF and RREF. RREF requires each pivot to be 1 and the only non-zero entry in its column.
Do not confuse row operations with column operations when constructing \(P\) and \(Q\).
Do not assume a matrix has an inverse merely because it is square. Its determinant must be non-zero.
Do not use the Rouché-Capelli theorem without comparing both ranks.
Do not say every homogeneous system has only the trivial solution. Non-trivial solutions occur when rank is less than the number of unknowns.
Do not include the zero vector in a linearly independent set.
Do not forget that eigenvectors must be non-zero.
Do not solve eigenvectors without first finding the eigenvalue.
Do not confuse eigenvalues with eigenvectors.
Do not write the characteristic equation with the wrong sign convention halfway through a calculation.
Do not forget that trace is the sum and determinant is the product of eigenvalues.
Do not apply Cayley-Hamilton to a non-square matrix.
Do not find the inverse with Cayley-Hamilton if the determinant is zero.
Do not omit the identity matrix \(I\) while substituting into the characteristic polynomial.

## Common Mistakes: Unit 2: Sequences and series

Do not confuse a sequence with its associated series.
Do not assume that \(a_n\to0\) proves \(\sum a_n\) converges.
Do not forget the exact threshold \(p>1\) for the \(p\)-series.
Do not use direct comparison without proving the required inequality.
Do not use limit comparison if the ratio limit is zero or infinity and then claim equivalence without checking the appropriate one-sided implication.
Do not reverse the ratio-test quotient halfway through a calculation. The stated convention here uses \(a_{n+1}/a_n\).
Do not say the ratio or root test proves divergence when its limit is exactly 1.
Do not confuse the Raabe quotient with the ratio-test quotient.
Do not use the integral test unless positivity, continuity and eventual monotonic decrease are established.
Do not apply Leibniz's test without checking that \(b_n\to0\).
Do not call a series absolutely convergent just because its original alternating form converges.
Do not confuse conditional convergence with divergence.
Do not rearrange a conditionally convergent series and assume its sum remains unchanged.
Do not forget that absolute convergence implies convergence.

## Common Mistakes: Unit 3: Differential equations

Do not confuse the order of a differential equation with its degree.
Do not calculate degree before making sure the equation is polynomial in derivatives.
Do not interchange \(M_y\) and \(N_x\) in the exactness condition.
Do not claim a differential equation is exact without verifying the equality.
Do not forget the arbitrary function \(g(y)\) after integrating \(M\) with respect to \(x\).
Do not differentiate the potential function with respect to the wrong variable.
Do not interchange the numerator or denominator signs in integrating-factor Rules I and II.
Do not apply a homogeneous integrating factor without checking that \(M,N\) are homogeneous of the same degree.
Do not forget the integrating constant in a linear differential equation.
Do not use the linear equation's integrating factor \(e^{\int Pdx}\) when \(P\) has not been properly identified.
Do not forget to substitute \(v=y^{1-n}\) in a Bernoulli equation.
Do not divide by a power of \(y\) without checking the excluded solution \(y=0\).
Do not confuse complementary function with particular integral.
Do not omit the complete solution \(y=CF+PI\).
Do not use the repeated-root CF formula for distinct roots.
Do not forget the factor \(x\) for repeated roots.
Do not use trigonometric CF for real roots.
Do not use the exponential PI shortcut when \(f(a)=0\).
Do not omit the \(x\) multiplier in the simple resonance failure rule.
Do not calculate variation-of-parameters integrals without first finding the Wronskian.
Do not use variation-of-parameters formulas before normalizing the coefficient of \(y''\) to 1.
Do not confuse \(D=d/dx\) with \(D_1=d/dz\).
Do not use \(x=e^z\) without transforming the derivatives.
Do not forget to substitute back from \(z\) to the original variable.

# HIGH-YIELD CLOSING SECTION C: QUICK-REVISION SUMMARY FORMULA SHEET


## Unit 1: Matrix formulas

Transpose
\[ (A^T)^T=A \]
\[ (AB)^T=B^TA^T \]
Symmetric matrix
\[ A^T=A \]
Skew-symmetric matrix
\[ A^T=-A \]
Orthogonal matrix
\[ A^TA=I \]
\[ A^{-1}=A^T \]
Unitary matrix
\[ A^*A=I \]
Idempotent matrix
\[ A^2=A \]
Involutory matrix
\[ A^2=I \]
Adjoint identity
\[ A\operatorname{adj}(A)=|A|I \]
Inverse
\[ A^{-1}=\frac{\operatorname{adj}(A)}{|A|} \]
Trace
\[ \operatorname{tr}(A)=\sum a_{ii} \]
Rank
\[ \operatorname{rank}(A)\le\min(m,n) \]
Canonical form
\[ PAQ= \begin{bmatrix} I_r&0\\ 0&0 \end{bmatrix} \]
Rouché-Capelli
\[ r(A)=r([A|B]) \]
Unique solution
\[ r(A)=r([A|B])=n \]
Infinite solutions
\[ r(A)=r([A|B])<n \]
Inconsistent
\[ r(A)\ne r([A|B]) \]
Homogeneous system with non-trivial solutions
\[ r(A)<n \]
Rank-nullity
\[ r(A)+\operatorname{nullity}(A)=n \]
Characteristic equation
\[ |A-\lambda I|=0 \]
Trace-eigenvalue property
\[ \operatorname{tr}(A)=\sum\lambda_i \]
Determinant-eigenvalue property
\[ |A|=\prod\lambda_i \]
Cayley-Hamilton theorem
\[ A^n+c_1A^{n-1}+\cdots+c_nI=O \]
For \(2\times2\):
\[ A^2-\operatorname{tr}(A)A+|A|I=O \]

## Unit 2: Sequence and series formulas

Geometric partial sum
\[ S_n=\frac{a(1-r^n)}{1-r} \]
Infinite geometric sum
\[ S=\frac{a}{1-r},\quad |r|<1 \]
\(p\)-series
\[ \sum_{n=1}^{\infty}\frac1{n^p} \]
\[ p>1:\text{ convergent} \]
\[ p\le1:\text{ divergent} \]
Direct comparison
\[ 0\le a_n\le b_n \]
Limit comparison
\[ L=\lim_{n\to\infty}\frac{a_n}{b_n} \]
Ratio test
\[ L=\lim_{n\to\infty} \left|\frac{a_{n+1}}{a_n}\right| \]
Root test
\[ L=\limsup_{n\to\infty}\sqrt[n]{|a_n|} \]
Raabe test
\[ R=\lim_{n\to\infty} n\left(\frac{a_n}{a_{n+1}}-1\right) \]
Gauss test
\[ \frac{a_n}{a_{n+1}} =1+\frac{\alpha}{n} +O(n^{-1-\delta}) \]
Logarithmic test
\[ L=\lim_{n\to\infty} \frac{\log(1/a_n)}{\log n} \]
Integral test
\[ \sum a_n \quad\Longleftrightarrow\quad \int f(x)\,dx \]
under positive, continuous and decreasing conditions.
Leibniz test
\[ \sum(-1)^{n-1}b_n \]
Converges when:
\[ b_n\ge0,\quad b_{n+1}\le b_n,\quad b_n\to0 \]
Absolute convergence
\[ \sum|a_n|<\infty \]
Conditional convergence
\[ \sum a_n\text{ converges},\quad \sum|a_n|\text{ diverges} \]

## Unit 3: Differential equation formulas

Exactness
\[ M_y=N_x \]
Exact solution
\[ F(x,y)=C \]
Integrating factor Rule I
\[ IF=e^{\int\frac{M_y-N_x}{N}\,dx} \]
when the quotient is a function of \(x\) alone.
Integrating factor Rule II
\[ IF=e^{\int\frac{N_x-M_y}{M}\,dy} \]
when the quotient is a function of \(y\) alone.
Linear differential equation
\[ y'+Py=Q \]
Integrating factor
\[ IF=e^{\int Pdx} \]
General solution
\[ y(IF)=\int Q(IF)\,dx+C \]
Bernoulli
\[ y'+Py=Qy^n \]
\[ v=y^{1-n} \]
\[ v'+(1-n)Pv=(1-n)Q \]
Constant-coefficient equation
\[ f(D)y=X \]
Complete solution
\[ y=CF+PI \]
Auxiliary equation
\[ f(m)=0 \]
Distinct roots
\[ CF=C_1e^{m_1x}+C_2e^{m_2x} \]
Repeated roots
\[ CF=e^{mx}(C_1+C_2x) \]
Complex roots
\[ CF=e^{\alpha x} (C_1\cos\beta x+C_2\sin\beta x) \]
Exponential PI
\[ PI=\frac{e^{ax}}{f(a)},\quad f(a)\ne0 \]
Simple failure case
\[ PI=\frac{xe^{ax}}{f'(a)} \]
Exponential shift
\[ \frac1{f(D)}e^{ax}V = e^{ax}\frac1{f(D+a)}V \]
Variation of parameters
\[ W=y_1y_2'-y_2y_1' \]
\[ u=-\int\frac{y_2R}{W}\,dx \]
\[ v=\int\frac{y_1R}{W}\,dx \]
\[ PI=uy_1+vy_2 \]
Cauchy-Euler trial solution
\[ y=x^m \]
Cauchy-Euler auxiliary equation
\[ am(m-1)+bm+c=0 \]
Cauchy substitution
\[ x=e^z,\quad D_1=\frac{d}{dz} \]
\[ xy'=D_1y \]
\[ x^2y''=D_1(D_1-1)y \]
Legendre substitution
\[ ax+b=e^z \]
\[ (ax+b)y'=aD_1y \]
\[ (ax+b)^2y''=a^2D_1(D_1-1)y \]

# FINAL EXAM PREPARATION PRIORITY

These are suggested study priorities based on the repository's syllabus coverage and the amount of mathematical working required. They are not verified CU past-paper frequency statistics.

| Priority Level | Target Unit | High-Yield Topics to Practise |
| :--- | :--- | :--- |
| **Very high** | Unit 1 | Rank, REF/RREF, consistency, eigenvalues/eigenvectors, Cayley-Hamilton inverse |
| **Very high** | Unit 2 | Ratio, root, Raabe, Gauss, integral, Leibniz and absolute convergence tests |
| **Very high** | Unit 3 | Exact equations, integrating factors, linear and Bernoulli equations |
| **Very high** | Unit 3 | Auxiliary equation, CF root cases and PI |
| **High** | Unit 3 | Variation of parameters and Cauchy-Euler equations |
| **High** | Unit 1 | Normal form and \(PAQ\) |
| **High** | Unit 2 | Sequence convergence, geometric series and \(p\)-series |
| **Syllabus self-study** | Unit 1 | Diagonalization and modal matrix |
| **Syllabus self-study** | Unit 2 | Half-range Fourier sine and cosine series |


# Source and scope notes

The source's official syllabus says Cayley-Hamilton theorem is taught without proof. Proof outlines are included as optional study support.
The source's official syllabus says the convergence tests are taught without proofs. The theorem statements and conditions are therefore the exam-essential portion; the additional explanations help with choosing and applying tests.
Diagonalization and modal matrices are listed as advanced-learner self-study in the official syllabus, not as core Unit I syllabus content.
Half-range Fourier series is listed as Unit II self-study. It is not expanded into a main chapter here because it was not included in your requested coverage.
Integrating-factor Rules III, IV and V have incomplete extracted slide formulas. The standard homogeneous and special-form material has been supplied, but I have not claimed to verify every rule against the original slide image.
The worked examples are newly constructed exam-standard exercises based on the repository's syllabus topics, not claimed to be previously asked CU questions.
Repository: [KishanKumar-in/cu-mathematics-1](https://github.com/KishanKumar-in/cu-mathematics-1?utm_source=chatgpt.com)
Master notes: [Open the complete Mathematics-I master file](https://github.com/KishanKumar-in/cu-mathematics-1/blob/main/_COMPLETE_CONT_26SMT-121%20__%20MATHEMATICS-I_SEMESTER_MASTER.md?utm_source=chatgpt.com)
