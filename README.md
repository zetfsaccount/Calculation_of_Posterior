Based on: http://www.cns.nyu.edu/malab/bayesianbook.html
# Bayesian-Inference-for-Vision
Calculation of the Posterior
Question:
Let us numerically calculate the posterior (1). Suppose the stimulus distribution p(s) is Gaussian with a mean of 20 and a standard deviation of 4. The measurement distribution p(x|s) is Gaussian with a standard deviation σ = 5. A Bayesian observer infers s from an observed measurement xobs = 30. We are now going to calculate the posterior pdf using numerical methods.

a) Define a vector of hypothesized stimulus values s: [0, 0.2, 0.4, . . . , 40].
b) Compute the likelihood function and the prior on this vector of s values.
c) Multiply the likelihood and the prior (pointwise).
d) Divide this product by its sum over all s (normalization step).
e) Convert this posterior probability mass function into a probability density function by dividing by the step size you used in your vector of s values (e.g., 0.2).
f) Plot the likelihood, prior, and posterior in the same plot.
g) Is the posterior wider or narrower than likelihood and prior? Do you expect this based on the equations we discussed?
h) Compute the theoretical posterior function on the vector of s values, and plot it together with the one you obtained in step (e). Are they consistent?
i) Change the standard deviation of the measurement distribution to a large value, repeat steps (a)-(f). What happens to the posterior? Can you explain this?
j) Change the standard deviation of the measurement distribution to a small value. What happens to the posterior? Can you explain this?

2) Problem 3.6 from the text: Submit a Colab notebook.

Let us numerically calculate the posterior (2). Start with the code from the above numerical example with two Gaussians. Suppose the stimulus distribution p(s) is uniform on the interval [−15,25] and 0 outside this interval. The measurement distribution p(x|s) is Gaussian with a standard deviation σ = 5. A Bayesian observer infers s from an observed measurement xobs = 30. We are now going to calculate the posterior pdf numerically.

a) What is the value of p(s) on the interval [−15,25]?
b) Repeat parts (a)-(f) from the previous numerical (Gaussians) problem for this new stimulus distribution.
c) Is the posterior Gaussian?
d) Numerically calculate the mean of the posterior.
e) Numerically calculate the variance of the posterior.
