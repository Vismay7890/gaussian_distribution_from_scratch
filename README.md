# gaussian_distribution_from_scratch
A simple python program using a few libraries to show the gaussian distribution of the randomly generated data arond mean with vairance sigma.
In this python code , firstly we import numpy , cmath for mathematical calculations and matplotlib for plotting the gaussian distribution of our data.
In initial lines of code ,  we  generate a random input variable x with use of "linspace" in numpy.
Then we compute the mean and variance usin the numpy functions "np.mean" for mean and "np.var" for variance.
Using the gaussian distribution equation that is ... N(X|mu,sigma^2) = 1/sqrt(2*pi*sigma^2) * e^(-(x-mu)^2/2*sigma^2).
Thereafter using this probability distribution we plot the gaussian curve in matplotlib and understand the data.
