# Convergence of Riemannian Broyden Family of Quasi-Newton Methods with Wolfe Line Search

**Author:** Xie Zhilin

## Abstract

We study the global convergence of a Riemannian Broyden family of quasi-Newton methods on complete Riemannian manifolds. The algorithm approximates the Riemannian Hessian via a convex combination of DFP and BFGS updates, transported between tangent spaces by an isometric vector transport satisfying a locking condition. This essay is mainly based on Chapter 4 of Huang (2014).

## Contents

1. **Introduction and Preliminaries**
   - Quasi-Newton Methods in Euclidean Space (DFP, BFGS, Wolfe conditions)
   - Notations and Definitions in Riemannian Geometry (tensors, manifolds, tangent spaces, connections, retraction, vector transport)
2. **Frame of Riemannian Broyden's Method**
   - Secant Equation on Riemannian Manifolds
   - Secant Equation with General Retraction and Vector Transport
   - Broyden's Update on Riemannian Manifolds
   - Wolfe Line Search on Riemannian Manifolds
   - Locking Condition
3. **Convergence Analysis**
   - Locking Condition
   - Basic Assumptions
   - Preliminary Results
   - Main Result

## References

The main reference is:

- Huang, W. (2014). *Optimization algorithms on Riemannian manifolds with applications*. PhD thesis, Florida State University.

Other key references include Absil (2008), Nocedal & Wright (2006), and Yuan (1995). See `ref.bib` for the full bibliography.
