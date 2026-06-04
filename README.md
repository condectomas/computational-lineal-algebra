# Computational Lineal Algebra

A collection of Python-based numerical linear algebra implementations. This repository bridges the gap between abstract algebraic structures and computational algorithms, focusing on tensor operations, basis transformations, and matrix decompositions.

## Core Projects

* **Vector Spaces & Hermitian Matrices (`hermitian_matrices_basis.ipynb`):** Constructs and validates orthonormal bases for $2 \times 2$ and $4 \times 4$ Hermitian matrices using Pauli matrices. Implements basis transformations, Kronecker products, and the matrix representation of the adjoint operator $\mathrm{ad}(H)$.
* **Coupled Oscillators & Matrix Exponentials (`coupled_oscillators_algebra.ipynb`):** Simulates the time evolution of a coupled mass-spring system. Computes matrix square roots and matrix exponentials ($e^{i t \sqrt{A}}$) via `scipy.linalg` to solve the continuous-time dynamic equations.
* **Tensor Algebra & Contraction (`tensor_algebra_contraction.ipynb`):** Demonstrates tensor coordinate transformations under basis changes in $\mathbb{R}^3$. Explicitly computes transformations for $(2,2)$, $(4,0)$, and $(0,4)$ tensors and visualizes tensor contraction as algorithmic index reduction.
* **Jordan Canonical Form (`jordan_canonical_form.ipynb`):** An algorithmic exploration of the minimal polynomial and generalized eigenspaces. Computes Jordan chains to transition non-diagonalizable linear maps into their simplest matrix representation.

## Technologies Used
* **Python**
* **NumPy:** For high-performance, vectorized tensor and matrix operations.
* **SciPy (`scipy.linalg`):** For advanced matrix decompositions and exponential propagators.
* **SymPy:** For symbolic algebraic verification.

---
*Note: All algorithms emphasize numerical stability, reproducible structures, and vectorized efficiency over standard iterative loops.*
