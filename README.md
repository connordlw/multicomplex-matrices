# multicomplex-matrices
This repository contains the diagonalizations of J matrices used in the matrix multicomplex step differentiation method.

The diagonalizations are contained in text files titled "J(k)", where (k) = 2^n denotes the highest order of derivative which can be computed using the matrix.
Diagonalizations are stored as three arrays in MATLAB format:

A 1xk array containing the eigenvalues for the J matrix.

A kxk array containing the eigenvectors for the J matrix.

A kxk array containing the inverse of the eigenvector matrix.
