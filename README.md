# Generative modelling with jump-diffusions (jumpAI)

https://arxiv.org/abs/2503.06558

This GitHub repository contains the **Mathematica** implementation of the jump-diffusion Laplace model for the example of heavy-tailed data samples:

1. Numerical evaluation of the generalized score function. The discretized form is also provided separately in the file "levyscore_rt200.mx" for a discretization of 200 points in x and t directions each.
2. Generation of samples from the heavy-tailed target distribution (symmetric alpha-stable distribution with alpha=1.7)
3. Estimation of the generalized score function using a simple neural network
4. ODE and SDE generation of new samples using exponential integrators
