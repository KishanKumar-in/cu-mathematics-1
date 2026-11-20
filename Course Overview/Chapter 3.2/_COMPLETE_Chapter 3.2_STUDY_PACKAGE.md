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
