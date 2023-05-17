# wqu-capstone-VIX-RSI-metric
Using VIX based RSI measures to time markets

VIX RSI based indicator
Sell when VIX RSI is lower than VIX RSI lower band as this means VIX is going to rise which means underlying stock/security/index price should fall
Buy when VIX RSI is higher than VIX RSI upper band as this means VIX is going to fall which means underlying stock/security/index price should rise

## Libraries required to be installed
### 1. statsmodels (for AD Fuller test)
pip install statsmodels

### 2. yfinance (yahoo finance)
pip install yfinance

### 3. pandas_ta (for financial technical analysis tools)
pip install pandas_ta

### 4. plotly (for plotting interactive graphs)
pip install plotly

### 5. cufflinks (for connecting plotly with pandas to create graphs and charts of dataframes directly)
pip install cufflinks

We have QuantFig object of cufflinks library to plot candlesticks and other widely used technical analysis tools. One can refer to below link for more details:
https://github.com/santosjorge/cufflinks
