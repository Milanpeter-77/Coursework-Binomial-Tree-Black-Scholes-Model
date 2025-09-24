# Modeling S&P 500 Dynamics and Pricing with Binomial Trees

Our task has two main parts.
First, in the **Returns** section, we work with historical monthly S\&P-500 data to calculate and model returns.
We estimate the mean and volatility, test whether the mean return differs from zero, and explore how much data is needed to pin down estimates precisely.
We also simulate return paths to verify our results, study how parameter uncertainty affects investment decisions, and compare two different models for the index dynamics.
Finally, we use these models to forecast the index, simulate its distribution, and value simple digital options.

In the **Binomial Trees** section, we shift focus to option pricing.
We construct binomial trees for the S\&P-500 step by step, ensuring that they match empirical variance and expected return.
We then compute option prices both with the tree and with the Black-Scholes formula, compare the outcomes, and study how results converge as the number of steps increases.
We also examine probability distributions under the risk-neutral measure, extend the framework to put options, verify put-call parity, and finally allow for early exercise to evaluate American options.

Together, these two parts train us to move from modeling returns to applying them in option pricing.
