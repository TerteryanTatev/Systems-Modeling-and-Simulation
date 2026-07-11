# Markov Chain State Simulation & Stationary Distribution Analysis

This folder contains a comprehensive mathematical simulation of a discrete-time Markov Chain modeling customer behavior states within a service ecosystem (hotel booking and stay lifecycle).

##  Implemented Methodology
* **Transition Matrix Formulations:** Constructing exact state-transition probability matrices ($P$) to map structural probability weights across multi-state configurations.
* **Stationary Distribution Calculations:** Solving for long-term equilibrium vectors ($\pi$) using dual analytical methods: solving the linear system $\pi P = \pi$ and performing Eigenvalue/Eigenvector decomposition.
* **Empirical Monte Carlo Simulation:** Running long-horizon stochastic trajectory generations to compute empirical state convergence rates.
* **Comprehensive Visual Dashboard:** Rendering correlation heatmaps, state-probability trajectories, and multi-axes subplots via `matplotlib` to compare theoretical vs. empirical metrics.

##  Technologies Used
* **Python 3**
* **NumPy:** For matrix mathematics, dot products, and eigenvalue solutions.
* **Pandas:** For structural dataframe tracking.
* **Matplotlib & Seaborn:** For plotting multi-layered subplot configurations and conditional heatmaps.
