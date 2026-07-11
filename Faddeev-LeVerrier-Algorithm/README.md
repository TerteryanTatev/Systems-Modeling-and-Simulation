# Faddeev–LeVerrier Algorithm for Matrix Analysis

This project implements the **Faddeev–LeVerrier algorithm** for computing the **characteristic polynomial** of a square matrix and its **inverse** through an iterative numerical approach.

## Features

* Computes the coefficients of the characteristic polynomial using the Faddeev–LeVerrier recursion.
* Calculates the inverse of a non-singular matrix without Gaussian elimination.
* Performs automatic verification by checking that (A \times A^{-1} = I).
* Displays the characteristic polynomial in a symbolic form.

## Algorithm Overview

The implementation follows the classical Faddeev–LeVerrier procedure:

1. Recursively computes the coefficients of the characteristic polynomial using matrix traces.
2. Constructs intermediate matrices required by the algorithm.
3. Derives the inverse matrix from the final iteration when the matrix is invertible.
4. Verifies the correctness of the computed inverse.

## Technologies

* **Python 3**
* **NumPy** – Matrix operations, identity matrices, and trace calculations.
* **SymPy** – Symbolic mathematics and characteristic polynomial representation.

## Output

The program provides:

* Characteristic polynomial coefficients
* Characteristic polynomial
* Inverse matrix (if it exists)
* Verification that

[
A \cdot A^{-1} = I
]

## Mathematical Background

The Faddeev–LeVerrier algorithm is a recursive method in numerical linear algebra that computes the coefficients of the characteristic polynomial of a square matrix. An important property of the algorithm is that it also enables the computation of the inverse matrix using the intermediate matrices generated during the recursion, provided the determinant is non-zero.
