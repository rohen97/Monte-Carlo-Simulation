# Monte-Carlo-Simulation
Used the monthly returns of the ten industry portfolios to generate the minimum-variance frontier  without short sales, using Monte Carlo simulation. 

Stock Valuation

Part 1: Performance Measurement
Risk_Factors.xlsx contains monthly observations of the risk-free rate and the three Fama–French risk factors, 
all expressed as a percentage. These observations cover the ten-year period from Jan 2004 through Dec 2013.

Using excess returns for the ten industry portfolios, calculate the following performance metrics:
1. Sharpe ratio
2. Sortino ratio (with risk-free rate as target)
3. Jensen's alpha
4. Three-factor alpha
Create a table showing the performance metrics for the ten industry portfolios. 
Also plot your results as a bar chart for each performance metric. 
Briefly explain the economic significance of each performance metric.

Part 2: Minimum-Variance Frontier Revisited
Use the monthly returns of the ten industry portfolios to generate the minimum-variance frontier 
without short sales, using Monte Carlo simulation. 

Without short sales, portfolio weights will be limited to the range [0, 1]. 
Randomly draw each element of w, the vector of portfolio weights, from the uniform distribution in the range [0, 1]. 
Divide w by the sum of the portfolio weights, to ensure that the portfolio weights sum to one.

Use the normalized w to calculate the mean return and standard deviation of return. 
Repeat this process until you have at least 100,000 obervations. 
Plot the points with mean return on the vertical axis and standard deviation of return 
on the horizontal axis to show the minimum-variance frontier.

Repeat this entire process by simulating 1/w using the standard uniform distribution: i.e., 
take the reciprocal of the random draw from the standard uniform distribution as the portfolio weight. 
Plot your results to show the minimum-variance frontier on a separate graph.
