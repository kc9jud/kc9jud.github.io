---
title: "Symplectic No-Core Configuration Interaction (spncci)"
collection: codes
link: 'https://github.com/nd-nuclear-theory/spncci'
---
`spncci` is a code for ab initio calculations in an $\mathrm{Sp}(3,\mathbb{R})$
symmetry-adapted basis, via the symplectic no-core configuration interaction 
(SpNCCI) approach. Many-body Hamiltonian matrix elements are evaluated through 
a laddering procedure, involving $\mathrm{Sp}(3,\mathbb{R})$ and 
$\mathrm{SU}(3)$ group theoretical coefficients, leading to a dense Hamiltonian 
matrix, which is then diagonalized via the Lanczos algorithm. Algorithms are 
structured for efficient parallelization, in collaboration with Lawrence 
Berkeley National Laboratory (LBNL) Scalable Solvers group. Currently the code 
is OpenMP parallelized, with exploratory work on MPI/OpenMP implementation. 
Full MPI/OpenMP parallelization and integration with a distributed, iterative 
eigensolver for dense matrices with block structure is anticipated by early in 
the new allocation year.
