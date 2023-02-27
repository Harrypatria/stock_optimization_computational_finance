## Stock Optimization Computational Finance

### Portfolio selection problem
a probabilistic form of the portfolio selection problem is established in which the uncertainty of risky assets is considered through a probabilistic optimization problem. 

The optimal values corresponding to each random case were then stored as a comprehensive database of system responses. Then, by sorting the resulting optimal values from best to worst, the exceedance probabilities of return and risk rankings were calculated for each portfolio and presented in the form of frontier charts. 

### Solution using Monte Carlo
Monte Carlo (MC) based solutions encompass a wide array of algorithms that exploit repeat random sampling and uncertainty to solve large, complex and generally intractable mathematical problems. MC is akin to exhaustive search type solutions. However in MC framed problems, the input model parameters, initial, boundary and environmental conditions are unknown and or subject to a degree of uncertainty. Therefore a true exahuastive search is not possible. The aim of MC is to conduct repeat random sampling of the input space to generate large numbers (e.g. $n$ = 100,000) of “plausible realities” from which metrics, risk analyses, and further assessments are drawn. Thus one of the most challenging aspects of the monte carlo method is in determining accuracte covariances and probability distributions of the input parameter space.

Lets make some simplifying assumptions:

We have $1000 to invest $V$.
The risk-free rate is 0.03 (3 %). This is the return we can garuntee by instead putting our money in a savings account.
Stocks have a known and fixed starting price. The monthly returns of a stock follow a standard normal distribution.
Stocks

First let’s define some stocks that are avaliable to invest in. For simplicity the stocks are heuristically assignined with a range of average daily return $mu$ and volatility $sigma$ values. For a more realistic simulation, one could derive these values from actual investment instruments. 

My published articles on this field of computational finance can be found here:
Are Electric Vehicle Stocks in ASEAN Countries Investible during the Covid-19 Pandemic?
https://iopscience.iop.org/article/10.1088/1755-1315/997/1/012002/meta

Find all related articles using this code in my papers
https://scholar.google.com/citations?user=OJVjCmsAAAAJ&hl=en

Electric vehicle, as one of the low carbon footprints, has transformed a wide range of energy and public sectors. Utilizing the WHO Covid-19 pandemic statement, we search for the optimal portfolio from the top seven Electric Vehicle (EV) enterprises in ASEAN. Using the MonteCarlo simulation of optimal risky assets portfolio, we find that before and during the pandemic, the optimal portfolio weights differ significantly. Before (during) the pandemic, the investment weight of optimal portfolio consists of Toyota Motor Corporation 49.83% (42.99%), Star 8 Corporation 23.20% (9.73%), Hyundai Motor Corporation 20.81% (10.63%), BMW.DE 2.79% (32.08%), Honda Motor Company 2.56% (0.64%), Mitsubishi Motor Corporation 0.68% (0.09%), and Nissan Motor Co. 0.14% (3.84%). The Sharpe Ratio shows how during the pandemic, the portfolio of EV stocks give more excessive return compare to their risks, from 93.55% to 250.62%. These findings support the notion of how EV stocks are investible, especially during the Covid-19 pandemic.

### Instruction to my students at SBM MBA ITB, MSc Accounting UI, MSc Tech. ITS and MM Binus
  - Copy, modify and run the code lines
  - Select your sample of enterprises regarding the courseworks
  - Running the code on Jupyter Notebook and/or Google Colab
  - Write the reports, please refer to previous articles that I published with other students. It is encouraged to cite a sort of articles.
  - Drop me an email if you have any questions regarding the project assignment
