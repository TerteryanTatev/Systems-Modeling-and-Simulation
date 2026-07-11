# Faddeev-LeVerrier Algorithm for Matrix Analysis

This folder contains a numerical linear algebra project focused on computing the characteristic polynomial coefficients and the inverse of a square matrix using the Faddeev-LeVerrier algorithm.

##  Implemented Methodology
* **Characteristic Polynomial Estimation:** Recursively calculating the coefficients ($p_k$) of the matrix $A$ using structural trace operations ($\text{Tr}(A_k)$).
* **Matrix Inversion:** Utilizing the final stages of the LeVerrier iterations to algorithmically derive the exact inverse matrix ($A^{-1}$) without employing traditional Gaussian elimination.
* **Algebraic Verification:** Conducting automated validation checks ($A \cdot A^{-1} = I$) to confirm the numerical precision of the custom implementation.

##  Technologies Used
* **Python 3**
* **NumPy:** For high-performance matrix multiplications, identity matrix generations (`np.eye`), and trace operations (`np.trace`).
* **SymPy:** For analytical representation and symbolic printing of the final polynomial equations.
