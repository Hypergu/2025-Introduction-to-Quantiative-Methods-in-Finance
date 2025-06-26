
Mini-Project 1: Building High- and Low-Risk Portfolios
 
 I began by selecting 46 different stocks and computing their historical volatilities. I classified “high-risk” stocks as those with volatility above 0.5 (total of 9stocks) and “low-risk” stocks as those below 0.3 (total of 18  stocks). Using portfolio-optimization techniques, I then minimized the overall volatility for each group. Finally, I compared the returns of these two portfolios over the same periods to see their performance.

Mini-Project 2: Searching for Normality in Market Volatility
 
 For my second project, first, I analyzed NASDAQ’s daily volatility over the last ten years and confirmed that its overall distribution is not normal. Then, I applied a six-month sliding window (with three-month steps) and identified 13 subperiods whose volatility distributions did pass normality tests. Next, I attempted to improve normality by removing days when volatility deviated by more than one, two, or three standard deviations—but even after filtering out those extreme days, the distribution remained non-normal. Then I tried checking portfolios from the project 1 on normality: both of them didn’t pass normality tests. Finally, I tried constructing a portfolio of 45 stocks whose aggregate volatility would follow a normal distribution; by optimizing the weights, I did find a combination that met the normality criteria. All of the stock I considered didn’t have normal volatility by itself. 

Mini-Project 3: Exploring Black–Scholes Sensitivities
 
 In project three, I examined how Black–Scholes option prices depend on the underlying spot price and time to expiration. The results matched theory: for calls, the price curve starts nearly flat at low spot prices and then becomes almost linear with slope close to one; for puts, it’s the reverse. When looking at time dependence, both call and put values differ by a constant amount when the risk-free rate is zero—and by an almost constant amount when it’s nonzero—consistent with call–put parity. Over longer maturities, you can clearly see the asymptotic limits predicted by the formula.

Mini-Project 4: Delta-Hedging under Stochastic Volatility
 
 Finally, I explored how non-constant volatility affects delta-hedging strategies. I simulated various hedging rules under a suggested volatility model and observed that all strategies converge toward the Black–Scholes price, albeit at different rates. The fastest convergence occurred when I computed deltas using the average volatility over the hedge interval. I also ran experiments under the Heston model, applied the classic Black–Scholes delta, and found very high standard deviations in P&L—indicating that further work is needed to tailor hedges to mean-reverting volatility.

 Artem Aleshin.
