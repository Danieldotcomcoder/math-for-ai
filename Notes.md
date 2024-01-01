# Summary of Probability Theory

## Elements of Probability
- Introduces basic concepts of probability theory such as sample space, events, and probability measure.
- Defines conditional probability and independence of events.
- Example: Conditional probability is P(A|B) = P(A ∩ B)/P(B), which means the probability of event A given that event B has occurred.

## Random Variables
- Defines random variables as functions mapping outcomes to real numbers.
- Introduces different types of random variables, such as discrete and continuous, and their corresponding distribution functions, such as PMF and PDF.
- Example: A discrete random variable is X ∼ Binomial(n, p), which means the number of heads in n independent flips of a coin with heads probability p. A continuous random variable is X ∼ Normal(µ, σ^2), which means a Gaussian distribution with mean µ and variance σ^2.

## Expectation and Variance
- Defines the expectation and variance of a random variable as measures of its central tendency and dispersion.
- Shows some properties and formulas for calculating them.
- Example: Expectation is E[X] = ∑x∈Val(X) x pX(x) for a discrete random variable, and E[X] = ∫∞−∞ x fX(x) dx for a continuous random variable. Variance is Var[X] = E[(X − E[X])^2] = E[X^2] − E[X]^2.

## Some Common Random Variables
- Lists some common random variables and their distribution functions, such as Bernoulli, Binomial, Geometric, Poisson, Uniform, Exponential, and Normal.
- Shows their mean and variance values.
- Example: A common random variable is X ∼ Poisson(λ), which means a probability distribution over the nonnegative integers used for modeling the frequency of rare events. Its mean and variance are both λ.

## Multiple Random Variables
- Extends the concepts of probability, distribution, expectation, and variance to the case of multiple random variables.
- Introduces the notions of joint, marginal, and conditional distributions, as well as independence and covariance.
- Example: A joint distribution is fXY (x, y) = fX(x) fY (y) if X and Y are independent. Covariance is Cov[X, Y ] = E[XY ] − E[X]E[Y ].

## Random Vectors
- Defines random vectors as vectors of random variables.
- Introduces the multivariate Gaussian distribution as an important example of a probability distribution over random vectors.
- Example: A random vector is X = [X1 X2 ... Xn]^T, where Xi are random variables. A multivariate Gaussian distribution is X ∼ N (µ, Σ), where µ is the mean vector and Σ is the covariance matrix.
