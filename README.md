# Copulas and Dependence Modeling

Course project for *APM_3XO62_EP* at École Polytechnique (2024–2025). The notebook, written in French, proves the main results on copulas and then uses simulation to study dependence between random variables, ending with an application to credit risk.

## Contents

- **Basic properties.** Copulas with one coordinate fixed, the independence and comonotone copulas, the Fréchet–Hoeffding bounds, why the lower bound is a copula only in dimension 2, and convexity of the set of copulas.
- **Sklar's theorem.** Existence and uniqueness of the copula of a vector with continuous marginals, using the generalized inverse, and invariance of the copula under strictly increasing transformations.
- **Gaussian copulas.** Simulation of Gaussian vectors from Box–Muller samples.
- **Archimedean copulas.** Construction from the Laplace transform of a positive random variable. With a Gamma(1/θ, 1) variable this gives the Clayton family, simulated for θ from 0.01 to 100.
- **Credit risk.** Default times of 100 firms whose dependence is driven by a copula. Monte Carlo estimates of the probability of at least 5, 10 or 30 defaults within 5 years, and how stronger correlation in a Gaussian copula fattens the tail of the number of defaults.

## Running it

Python 3 with NumPy, SciPy and Matplotlib. Open `Copulas and Modeling of Dependence Between Random Variables.ipynb` in Jupyter and run the cells in order.
