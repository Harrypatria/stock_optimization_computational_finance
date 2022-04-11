# stock_optimization_computational_finance

# Portfolio selection problem
a probabilistic form of the portfolio selection problem is established in which the uncertainty of risky assets is considered through a probabilistic optimization problem. 

The optimal values corresponding to each random case were then stored as a comprehensive database of system responses. Then, by sorting the resulting optimal values from best to worst, the exceedance probabilities of return and risk rankings were calculated for each portfolio and presented in the form of frontier charts. 

# Solution using Monte Carlo
Monte Carlo (MC) based solutions encompass a wide array of algorithms that exploit repeat random sampling and uncertainty to solve large, complex and generally intractable mathematical problems. MC is akin to exhaustive search type solutions. However in MC framed problems, the input model parameters, initial, boundary and environmental conditions are unknown and or subject to a degree of uncertainty. Therefore a true exahuastive search is not possible. The aim of MC is to conduct repeat random sampling of the input space to generate large numbers (e.g. $n$ = 100,000) of “plausible realities” from which metrics, risk analyses, and further assessments are drawn. Thus one of the most challenging aspects of the monte carlo method is in determining accuracte covariances and probability distributions of the input parameter space.

Lets make some simplifying assumptions:

We have $1000 to invest $V$.
The risk-free rate is 0.03 (3 %). This is the return we can garuntee by instead putting our money in a savings account.
Stocks have a known and fixed starting price. The monthly returns of a stock follow a standard normal distribution.
Stocks

First let’s define some stocks that are avaliable to invest in. For simplicity the stocks are heuristically assignined with a range of average daily return $mu$ and volatility $sigma$ values. For a more realistic simulation, one could derive these values from actual investment instruments. 
