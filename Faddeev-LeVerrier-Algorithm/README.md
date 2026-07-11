# Faddeev–LeVerrier Algorithm for Matrix Analysis

This project implements the **Faddeev–LeVerrier algorithm** for computing the **characteristic polynomial** and the **inverse** of a square matrix using an iterative numerical approach.

## Features

- Computes the coefficients of the characteristic polynomial using the Faddeev–LeVerrier recursion.
- Calculates the inverse of a non-singular matrix without using Gaussian elimination.
- Performs automatic verification by checking that **A · A<sup>-1</sup> = I**.
- Displays the characteristic polynomial in symbolic form.

## Algorithm Overview

The implementation follows the classical Faddeev–LeVerrier procedure:

1. Recursively computes the coefficients of the characteristic polynomial using matrix trace operations.
2. Constructs the intermediate matrices required by the algorithm.
3. Derives the inverse matrix from the final iteration when the matrix is invertible.
4. Verifies the correctness of the computed inverse.

## Technologies

- **Python 3**
- **NumPy** – Matrix multiplication, identity matrix generation (`np.eye`), and trace computation (`np.trace`).
- **SymPy** – Symbolic mathematics and characteristic polynomial representation.

## Output

The program provides:

- Characteristic polynomial coefficients
- Characteristic polynomial
- Inverse matrix (if it exists)
- Verification that **A · A<sup>-1</sup> = I**

## Mathematical Background

The **Faddeev–LeVerrier algorithm** is a classical recursive method in numerical linear algebra used to compute the coefficients of the characteristic polynomial of a square matrix.

One of the key advantages of the algorithm is that, in addition to determining the characteristic polynomial, it can also compute the inverse of a non-singular matrix using the intermediate matrices generated during the recursion. This eliminates the need for traditional inversion techniques such as Gaussian elimination.

The implementation also performs a verification step by confirming that the product of the original matrix and the computed inverse equals the identity matrix:

**A · A<sup>-1</sup> = I**
