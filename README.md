# FinTech Consultancy Firm: Financial Health Tools

In this project, I have developed two financial analysis tools to help individuals assess their financial health and plan for retirement.


## Background
At the FinTech Consultancy Firm, our mission is to make a positive impact on local communities by providing financial solutions that enhance the financial health of individuals. We recently secured our first contract with one of the largest credit unions in the area. The credit union wants to develop a tool that helps its members assess their monthly personal finances and plan for retirement with investments in cryptocurrencies, stocks, and bonds.

## Resources
To build these financial analysis tools, we used the following APIs:
- [Alpaca Markets API](https://alpaca.markets/docs/api-documentation/) - Used to pull historical stocks and bonds information.
- [Coin API](https://www.coinapi.io/) - Used to retrieve Bitcoin and Ethereum prices.

## Instructions

### Part 1 - Personal Finance Planner
In this section of the challenge, we created a personal finance planner application that allows users to visualise their savings composed of investments in shares and cryptocurrencies and assess if they have enough money as an emergency fund. Here are the steps we followed:

1. **Collect Crypto Prices Using the requests Library**
   - We collected current prices of Bitcoin (BTC) and Ethereum (ETH) using the Alternative Free Crypto API.
   - The prices were used to compute the portfolio value of cryptocurrencies.

2. **Collect Investments Data Using Alpaca: SPY (stocks) and AGG (bonds)**
   - We collected the current closing prices for SPY (stocks) and AGG (bonds) using the Alpaca API.
   - The closing prices were used to compute the value of the current amount of shares.

3. **Savings Health Analysis**
   - We analysed the financial health of the credit union's members.
   - We created a DataFrame to consolidate the total value of crypto assets and shares.
   - We plotted a pie chart to visualise the composition of personal savings.
   - We used conditional statements to validate if the current savings are enough for an emergency fund.

### Part 2 - Retirement Planning
In this section, we developed a retirement planning tool that uses Monte Carlo simulations to project portfolio performance over 30 years. Here are the steps we followed:

1. **Monte Carlo Simulation**
   - We configured a Monte Carlo simulation to forecast 30 years of cumulative returns for a portfolio composed of stocks (SPY) and bonds (AGG).

2. **Retirement Analysis**
   - We fetched summary statistics from the Monte Carlo simulation results, providing insights into the range of possible outcomes.
   - We calculated the expected portfolio return at the 95% lower and upper confidence intervals based on an initial investment of $20,000.
   - We also calculated the expected portfolio return at the 95% lower and upper confidence intervals based on a 50% increase in the initial investment.

<br>

Thank you for choosing our FinTech consultancy firm for your financial analysis needs. We look forward to assisting you in achieving your financial goals and ensuring your financial well-being.
