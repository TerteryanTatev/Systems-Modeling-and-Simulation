# Polynomial Interpolation (Lagrange Method)

This folder contains a numerical computation project focused on Polynomial Interpolation using the classical Lagrange methodology to approximate analytical functions from finite experimental datasets.

##  Implemented Methodology
* **Lagrange Polynomial Construction:** Constructing an exact $n$-th degree algebraic polynomial that sequentially passes through all pre-defined experimental coordinates ($X_i, f_i$).
* **Symbolic Expansion:** Leveraging symbolic computation algebra to dynamically expand, simplify, and print the resulting continuous interpolation function formula.
* **Exact Node Matching:** Verifying mathematical convergence where the calculated polynomial yields the absolute exact historical observations at the input sample points.

##  Technologies Used
* **Python 3**
* **NumPy & Pandas:** For coordinate array handling and structured analytical tracking.
* **SymPy:** For execution of symbolic algebraic operations, polynomial expansions, and formal printing.
