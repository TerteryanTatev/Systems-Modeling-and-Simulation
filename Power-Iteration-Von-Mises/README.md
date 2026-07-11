# Von Mises Power Iteration Method for Eigenvalues

This folder contains a numerical linear algebra project focused on computing the dominant eigenvalue ($\lambda_1$) and its corresponding eigenvector ($X_1$) of a square matrix using the Von Mises Power Iteration algorithm.

##  Implemented Methodology
* **Dominant Eigenpair Estimation:** Utilizing successive matrix-vector multiplications ($y_{k+1} = A \cdot y_k$) combined with dynamic vector normalization to converge towards the largest eigenvalue in magnitude.
* **Secondary Eigenvalue Extraction ($\lambda_2$):** Utilizing intermediate vector ratios and shifted iteration states to approximate the second dominant eigenvalue.
* **Convergence Criterion:** Implementing an automated convergence loop that terminates once the delta between consecutive eigenvalue approximations drops below a predefined tolerance ($\epsilon$).

##  Technologies Used
* **Python 3**
* **NumPy:** For vectorized array products (`@` operator), computing matrix norms (`np.linalg.norm`), and array manipulation.
