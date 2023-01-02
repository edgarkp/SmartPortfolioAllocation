# SmartPortfolioAllocation
This project implements an approach to smartly select a stock's optimal size to build one's portfolio. It is based on the modern portfolio theory introduced by Harry Markowitz

![](readme-images/Markowitz.png)
*Source: Investopedia*

The theory is described by a set of statistical procedures to determine the allocation that maximizes the portfolio's expected return and minimizes its associated risk. It is defined under the framework of a risk-return tradeoff graph.

![](readme-images/efficient-frontier.png)

### The dataset
The dataset provided is given by the Yahoo finance API and consists of stock data of the following companies that compose our portfolio:
1) BNP PARIBAS
2) IPSOS
3) METROPOLE TV
4) SANOFI 
5) DERICHBOURG
6) TOTAL ENERGIES
7) ACCENTURE
8) STMicro Electronics

Most of the companies have their data on the french market , except from Accenture whose stock is exchanged on the american market. Each stock data contains attributes that are recorded during a market day:

1) *Open :* Price of the stock at the market's opening.
2) *High :* Highest price of the stock during the market day.
3) *Low :* Lowest price of the stock during the market day.
4) *Close :* Price of the stock at the market's closing.
5) *Adj Close :* Adjusted price of the stock at the market's closing. It takes into account appropriate split and dividend multipliers
6) *Volume:* Volume of exchanged stocks.

### Exploratory Data Analysis
It contains the study of any correlation found between stock prices, descriptive statistics on individual expected returns and risks and profit evaluation for a portfolio with equal sizings (which will be the basis of our portfolio benchmark)

### Optimal sizing
The optimisation is performed using two popular methods: Monte Carlo & Least Square Error . The results of each method will be compared to the portfolio with equal sizings.

### To run the project
* Create a environment from the requirements.txt file (Conda environment + Windows-based only)
* Run the notebook *SmartAllocation*

### Closing
Feel free to comment and add any constructive critics that could help me better my solution :) 



