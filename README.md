This project utilises risk analytics to manage a cryptocurrency portfolio consisting of BTC, ETH, DOGE and MATIC.

It is split into three files.

The first file performs data analytics to review key metrics of each asset in terms of their daily log returns, annualised Sharpe ratios and asset correlations to gain an overview
of the asset components of the portfolio. Mean-variance optimisation to minimise risk is then performed to construct two portfolios, one with no maximum weight holding and the other 
with a maximum weight holding of 0.5. Key metrics analysis (VaR and ES) is then performed on each individual asset and the unrestricted portfolio.

The second file executes an option trading strategy of a long strangle to determine the optimal price to buy a call and put option in order to minimise downside risk and maximise
upside potential.

The last file performs the overall portfolio management using the Black Scholes formula to calculate a theoretical price based on a specific volatility. This calculated price is 
compared to the actual price ending that day. The differences in price serves as a trading signal.
