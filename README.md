Efficient Frontier:

The efficient frontier is a concept in modern portfolio theory that represents the set of optimal portfolios that offer the highest expected return for a given level of risk,
or the lowest risk for a given level of expected return. It is a fundamental concept in finance and investment, and is used to help investors make informed decisions about
constructing portfolios that balance risk and return according to their preferences and constraints.

**Mathematical Representation**

The efficient frontier can be mathematically represented using the following equations:

**Expected Return (ER)**

The expected return of a portfolio is calculated as the weighted average of the expected returns of the individual assets in the portfolio:

ER = Σ (w_i \* ER_i)

where w_i is the weight of the ith asset in the portfolio, ER_i is the expected return of the ith asset, and Σ denotes the sum over all assets in the portfolio.

**Risk (Standard Deviation)**

The risk of a portfolio is measured by its standard deviation, which is calculated as the square root of the variance of the portfolio returns:

σ = √(Σ (w_i \* σ_i)^2)

where σ_i is the standard deviation of the ith asset, and Σ denotes the sum over all assets in the portfolio.

**Efficient Frontier Equation**

The efficient frontier equation is a mathematical representation of the optimal portfolio that minimizes risk for a given level of expected return, or maximizes expected 
return for a given level of risk. It is typically represented as:

ER = r_f + β \* (ER_m - r_f)

where ER is the expected return of the portfolio, r_f is the risk-free rate, ER_m is the expected return of the market, and β is the beta of the portfolio.

**Portfolio Optimization**

The efficient frontier is constructed by optimizing the portfolio weights to find the optimal portfolio that minimizes risk for a given level of expected return,
or maximizes expected return for a given level of risk. This is typically done using linear programming or quadratic programming techniques.

**Example**

Suppose we have two assets, A and B, with the following characteristics:

| Asset | Expected Return | Standard Deviation |
| --- | --- | --- |
| A | 0.08 | 0.15 |
| B | 0.12 | 0.20 |

To construct the efficient frontier, we would calculate the expected return and risk of each asset, and then use the efficient frontier equation to find the optimal
portfolio weights that minimize risk for a given level of expected return, or maximize expected return for a given level of risk.

**The code includes:**
  Calculate the expected return and risk (standard deviation) of individual assets
  Construct the covariance matrix of the asset returns
  Optimize the portfolio weights to find the efficient frontier
  Plot the efficient frontier and the individual assets on a risk-return graph
