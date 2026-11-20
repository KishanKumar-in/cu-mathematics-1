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
