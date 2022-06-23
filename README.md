# ADMMBO
This package is an implementation of "ADMMBO, An ADMM Framework for Bayesian Optimization with Unknown Constraints'' in python language, to appear in the Journal of Machine Learning Research (JMLR), special issue on Bayesian Optimization

This package makes use of the following:
Numpy package,
sklearn package (GaussianProcessRegressor),
matplotlib.

The goal of the ADMMBO algorithm is to find the optima for a relatively expensive to compute objective function. This process is carried out by using the Alternating Direction Method of Multipliers with the process of Bayesian Optimization. The algorithm works best with smaller dimensionality (typically less than 20).

Paper:
https://www.jmlr.org/papers/volume20/18-227/18-227.pdf

