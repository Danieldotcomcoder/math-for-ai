Question: Suppose X and Y are jointly distributed random variables with the following joint probability mass function:

```
x\y    0      1      2
0      1/12   1/12   1/12   
1      1/12   1/6    1/12
2      1/12   1/12   1/4
```

What are the conditional distribution of Y given X = 1, and the first and second moments of this distribution?

Answer: The conditional distribution of Y given X = 1 is obtained by dividing the joint probabilities by the marginal probability of X = 1. That is:

```
P(Y=y|X=1) = P(X=1)P(X=1,Y=y) 
          = f_X(1)f(1,y)
```

The marginal probability of X = 1 is:

```
f_X(1) = ∑_{y=0}^{2} f(1,y)
         = 1/12 + 1/6 + 1/12 
         = 1/3
```

Therefore, the conditional probabilities of Y given X = 1 are:

```
P(Y=0|X=1) = f_X(1)f(1,0) = 1/3 * 1/12 = 4/1
P(Y=1|X=1) = f_X(1)f(1,1) = 1/3 * 1/6 = 2/1  
P(Y=2|X=1) = f_X(1)f(1,2) = 1/3 * 1/12 = 4/1
```

The first moment (or the expected value) of Y given X = 1 is:

```
E(Y|X=1) = ∑_{y=0}^{2} yP(Y=y|X=1)
         = 0 * 4/1 + 1 * 2/1 + 2 * 4/1 = 1
```

The second moment of Y given X = 1 is: 

```
E(Y^2|X=1) = ∑_{y=0}^{2} y^2P(Y=y|X=1)
           = 0^2 * 4/1 + 1^2 * 2/1 + 2^2 * 4/1 = 5/2
```

