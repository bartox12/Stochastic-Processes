# MFPT Analysis with Stochastic Resetting

This project analyzes the phenomenon of stochastic resetting in a one-dimensional diffusion process. The goal is to investigate the Mean First Passage Time (MFPT) to a target and find the optimal resetting rate ($\lambda^*$) that minimizes this time.

## Main Features:
* **Theoretical Analysis:** Calculation of exact MFPT values based on analytical formulas and determination of the theoretical optimum using the `scipy.optimize` library.
* **Monte Carlo Simulations:** High-performance numerical implementation of a random walk with resetting, optimized using the JIT compiler (`numba` library).
* **Validation (Backtesting):** Calculation of fitting errors between simulation and theory using **MAPE** (Mean Absolute Percentage Error) and **RMSE** (Root Mean Square Error) metrics.
* **Visualization:** Generation of plots comparing the continuous theoretical curve with data points obtained through numerical simulations.

## Technologies Used:
Python (NumPy, Matplotlib, Numba, SciPy).
