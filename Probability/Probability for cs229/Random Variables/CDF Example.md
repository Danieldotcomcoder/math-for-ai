```
Question: Suppose the lifetime of a light bulb follows an exponential distribution with a mean of 1000 hours. What is the probability that a light bulb will last more than 1200 hours?

Answer: Let X be the lifetime of a light bulb in hours. Then X has a probability density function given by:

f(x) = 1/1000 * e^(-1000x), x > 0

The cumulative distribution function of X is:

F(x) = ∫ from -∞ to x f(t) dt
     = ∫ from 0 to x 1/1000 * e^(-1000t) dt
     = 1 - e^(-1000x), x > 0

The probability that a light bulb will last more than 1200 hours is:

P(X > 1200) = 1 - P(X ≤ 1200)
           = 1 - F(1200)
           = 1 - (1 - e^(-1000/1200))
           = e^(-5/6) ≈ 0.301
```
