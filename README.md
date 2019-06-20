# Quantos-and-LookbackOptions-in-R

(1)	Path Dependent Options – Lookback options:
    a. Develop a program to generate price paths for a stock that follows a Geometric Brownian motion. Use the simulated paths to               estimate the price of two lookback options: 
        (a) an option with a payoff = {Max(S1,…,ST) – K}+
        (b) an option with a payoff = { ST - Min(S1,     …,ST)}+.
    b. Use the following parameter values: T = 1 year, Number of intervals = 12, r=3%, Sigma=25%.  Simulate option values based on 1,000       paths and 10,000 paths.  Present results for option value and 95% confidence bounds.

(2)	Quantos:
    a. Quantos are options on a foreign stock with payoffs in the foreign currency. The option buyer will convert domestic currency into        foreign currency at the time of expiration. Both the stock price, denominated in the foreign currency, and the exchange rate              follow a Geometric Brownian motion.
    b. Assume that a European investor buys an at-the-money option and will convert Euros to Dollars at maturity, i.e. the payoff =              {S1(T)*S2(T) – K}+.  {S1(t) is the price of the stock at time t in USD and S2(T) is the EURO/USD exchange rate, and K is in Euros.        Set the strike price in Euros using the current exchange rate, e.g. for an at-the-money option, the strike price is equal to Euro        S1(0) * S2(0). Let the maturity of the option be 3 months.
    c. Estimate the volatility of stock returns and the changes in the EURO/USD exchange rate using historical data for a three month           period. Also estimate the correlation between the daily changes in the stock returns and exchange rate changes.  Use data                 downloaded from the internet.  Also get the 3-month USD and the 3-month Euro interest rate.
    d. Simulate 3-month returns for the Stock and Euro/USD exchange rate using a bivariate normal distribution that is consistent with         the observed correlation of the stock return and exchange rate.  Estimate the value of an at-the-money Quanto described above.           Provide 95% confidence bounds for simulations with 1,000 and 10,000 estimates.
