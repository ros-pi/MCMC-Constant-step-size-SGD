# MCMC-Constant-step-size-SGD
This repository provides a Python implementation and validation of the paper "Bridging the Gap between Constant Step Size SGD and Markov Chains" (Dieuleveut et al., 2017) [https://arxiv.org/abs/1707.06386].

The project treats Stochastic Gradient Descent (SGD) with a constant step-size as a homogenous Markov Chain. We implement:

 -   Logistic Regression from scratch to maintain full control over stochasticity.

 -   Polyak-Ruppert Averaging to minimize stochastic variance.

 -   Richardson-Romberg Extrapolation to eliminate the O(γ) asymptotic bias.

The code includes a comparison of error convergence rates (MSE) and visualizations of the stationary distribution πγ​, bridging the gap between optimization theory and MCMC sampling logic.
