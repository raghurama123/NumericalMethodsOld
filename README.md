# NumericalMethods

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python3](https://img.shields.io/badge/Language-Python3-red.svg)](https://www.python.org/download/releases/3.0/)

This repository contains Jupyter notebooks, images, PDFs, etc. prepared for the course _Numerical Methods_ offered for Ph. D. students at TIFR Hyderabad (https://moldis-group.github.io/teaching.html)

## How to access this material?

First of all, this material is made available on the GitHub to encourage others to access it freely, maintain a local copy, and may be even contribute corrections or new material. So, you can follow the _three steps_ listed below freely, i.e., without having to commit to any responsibilities. 

1. If you think that you will ever use (or reuse) this material (or a part of it) for any purpose, you should sign-in to github by creating an account (maybe google account works for this too), and then click the 'Fork' button on the top-right. Then, you will get a local copy to play with. You will also be notified when any changes is made to this master version. You will be able to merge the new changes to your own copy of this repository. Others can also _pull_ the changes you make in your version.

2. To download the content to your computer, type the following in a terminal

```
git clone https://github.com/raghurama123/NumericalMethods.git
```

or click the 'code' botton above and then click 'Download zip'

_If you also Fork the material, then replace 'raghurama123' in the above line with your 'username'_

3. If you want to try the material in a web browser, i.e., to test the code or make small changes and run the code, you can access this repository at the interactive platform Binder by clicking the link: https://mybinder.org/v2/gh/raghurama123/NumericalMethods/HEAD

_If you also Fork the material, then replace 'raghurama123' in the above line with your 'username'_

## Syllabus: 

1. Python: Writing/running codes, Jupyter notebooks, modules

2. Linear Equations: Direct methods: Cramer's rule, row-reduction, forward/backward substitution, Gaussian elimination; LU factorization: Cholesky's method

3. Data Modeling: Approximations: least squares fitting; Interpolation: polynomial interpolation, `scipy.interpolate.interp1d`

4. Root finding: The problem, fixed-point iteration, bisection method, Newton-Raphson method (1-D and n-D), Jacobian matrix, pseudo-inverse, quasi-Newton method (1-D: secant method, n-D: Broyden), `scipy.optimize` 

5. Optimization/Minimization: 1-D problems, n-D problems, `scipy.optimize.minimize(method=’L-BFGS-B’)`, Simplex method, `scipy.optimize.minimize(method=’Nelder-Mead’)`, How to select an optimization method?

6. Numerical Differentiation: Finite difference; Error analysis

7. Numerical Integration: Newton-Cotes formulae, Romberg/Gaussian integration, Multiple integrals

8. Initial Value Problems: Euler/Runge-Kutta methods; Stability and Stiffness

9. Boundary Value Problems: Shooting Method

10. Symmetric Matrix Eigenvalue Problems: Jacobi rotations, Power/inverse power method, Tridiagonal form

11. Application to Chemical Physics: Molecular thermodynamics (Ideal gas, harmonic oscillator, rigid rotor partition functions), Equation of states, Schroedinger equation of Hydrogen molecule cation, Hartree-Fock for He atom, Linear variational problems in Quantum mechanics (1D potentials, Tunneling problems), Potential energy surface fitting, Time-dependent Schroedinger equation. 

12. Optional Topics: Krylov Subspace Techniques, Lanczos iteration, Iterative linear solvers, Non-linear regression, Matrices: Rank and condition numbers

## References:     
1. <img src="https://img.shields.io/badge/Language-Python-red.svg" align="right"/>Numerical Methods in Engineering with Python 3, Jaan Kiusalaas, Cambridge University Press (2013).    
2. <img src="https://img.shields.io/badge/Language-Python-red.svg" align="right"/>A Student’s Guide to Python for Physical Modeling, Jesse M. Kinder, Philip Nelson, Princeton University Press (2018).        
3. Numerical Methods, W. Boehm, H. Prautzsch, Universities Press (2000).     
4. <img src="https://img.shields.io/badge/Language-Matlab-blue.svg" align="right"/>Introduction to Numerical Computation, Lars Elden, Linde Wittmeyer-Koch, Hans Bruun Nielsen, Overseas Press (2006).     
5. <img src="https://img.shields.io/badge/Language-Fortran-green.svg" align="right"/>Elementary Numerical Analysis: An Algorithmic Approach, Samuel D. Conte, Carl de Boor, Edition 3, McGraw-Hill (1981).        
6. Introductory Numerical Analysis, Anthony J. Pettofrezzo, Dover (2006).     
7. <img src="https://img.shields.io/badge/Language-Fortran-green.svg" align="right"/> Elementary Theory and Application of Numerical Analysis, David G. Moursund, Charles S. Duris, Dover (1988).    

There are several interesting books on this topic, some are very extensive. The books listed above are known for their brevity and can be covered during a 3-4 months course. Some of the books contain codes in languages mentioned on the right side. However, the presentation in these books are generally applicable and make no reference to any particular programming language.

## Additional reading:    
[Introduction to object-oriented programming in Python with examples](https://www.programiz.com/python-programming/object-oriented-programming)     
[Square Roots from 1; 24, 51, 10 to Dan Shanks](https://www.maa.org/programs/maa-awards/writing-awards/square-roots-from-1-24-51-10-to-dan-shanks)      
[Babylon and the square root of 2](https://johncarlosbaez.wordpress.com/2011/12/02/babylon-and-the-square-root-of-2/)      
[PEP 8 — Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)   
[What Every Computer Scientist Should Know About Floating-Point Arithmetic](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)    

## Contact
For comments, questions, suggestions or requests please write to ramakrishnan@tifrh.res.in 

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/raghurama123.svg?style=social&label=%20%40raghurama123)](https://twitter.com/raghurama123)
