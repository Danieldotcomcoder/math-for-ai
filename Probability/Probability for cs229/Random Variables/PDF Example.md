Example:

Suppose the waiting time (in minutes) for a bus at a particular stop follows a uniform distribution between 0 and 10 minutes. Find the PDF of the waiting time.

Solution:

- Identify the distribution: The problem states the waiting time follows a uniform distribution.

- Determine the parameters: For a uniform distribution, we need the minimum (a) and maximum (b) values, which are 0 and 10 minutes, respectively.

- Apply the PDF formula: The PDF of a uniform distribution is:

  ```
  f(x) = 1 / (b - a), for a ≤ x ≤ b
  = 0, otherwise
  ```

- Substitute the values:

  ```
  f(x) = 1 / (10 - 0) = 1/10, for 0 ≤ x ≤ 10
  = 0, otherwise
  ```

- Interpretation:

  The PDF doesn't give probabilities directly for specific values (like PMF for discrete variables) because continuous variables can take on an infinite number of values.
  Instead, it describes the relative likelihood of different values within the range.
  Here, the PDF f(x) = 1/10 indicates that any waiting time between 0 and 10 minutes is equally likely.

Using the PDF:

- Calculate probabilities of events involving intervals:

  Probability of waiting 5 minutes or less: P(X ≤ 5) = ∫0^5 (1/10) dx = 1/2

  Probability of waiting between 3 and 7 minutes: P(3 ≤ X ≤ 7) = ∫3^7 (1/10) dx = 4/10 = 2/5

Key points:

- The PDF is a function, not a table like a PMF.
- It represents the relative likelihood of different values within a continuous range.
- The total area under the PDF curve must equal 1.
- You use calculus (integration) to calculate probabilities with PDFs.
