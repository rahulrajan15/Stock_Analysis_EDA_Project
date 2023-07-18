# Stock Market Analysis EDA Project
The project aims to conduct an exploratory analysis of the stock market, utilizing various techniques and tools to gain insights into the behavior and performance of stocks. 
By analyzing historical price data, fundamental metrics, volume trends, and volatility patterns, this project endeavors to provide valuable information for investors, traders, and financial analysts.

![18](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/a5e9e6bd-2d74-42aa-9834-b35eadbcbd65)

The analysis begins by retrieving the latest stock market data, focusing on the Open, High, Low, and Close (OHLC) prices. The last five rows of OHLC prices are displayed, allowing for a quick overview of recent market activity.
To accommodate multiple stocks, the solution accepts a list of ticker symbols, enabling the analysis of a diversified portfolio.
For a more detailed analysis, minute-level data can be fetched. The user can specify the desired time period and intervals, providing a granular view of stock price movements. 
This feature is especially useful for day traders or those interested in short-term market dynamics.

![21](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/563a9ddc-0a3a-4080-9e0e-86abcb85c6d6)

The project supports various types of visualizations, including volume charts, moving averages, scatter plots, histograms, and box plots. Moving averages can be plotted to identify trends and potential support/resistance levels for specific stocks. 
Correlation and scatter matrix graphs provide insights into the relationships between different stocks. Candlestick patterns can be plotted within a specified time period, aiding technical analysis. Histograms and kernel density estimates (KDE) offer visual representations of volatility and its distribution. 
Box plots can be created to compare the volatility of different stocks.

Lastly, cumulative returns of a particular stock can be calculated, providing a measure of the stock's performance over time. 
This information can be used to assess the profitability of an investment or compare the performance of multiple stocks.
Overall, this exploratory stock market analysis project aims to empower investors, traders, and 
analysts with a comprehensive set of tools and techniques to extract valuable insights from financial market data. 

# Technologies used are;
Python , Statistics

# Python Libraries
numpy, pandas, pandas_datareader, yfinance, datetime, matplotlib.pyplot, scatter_matrix, matplotlib.dates

# Data 
Yahoo Finance

# Issues faced by Stock Market Analysis
1) Data Quality and Accuracy: Stock market analysis heavily relies on accurate and reliable data. However, data inconsistencies, errors, or missing values can pose challenges and affect the accuracy of the analysis.
2) Market Volatility: The stock market is inherently volatile, driven by various factors such as economic events, geopolitical issues, and investor sentiment.
3) Data Overload: The stock market generates a vast amount of data, including price data, fundamental data, news articles, and social media sentiment.
4) Limited Historical Data: Historical data is crucial for analyzing long-term trends and patterns. However, obtaining a comprehensive historical dataset can be challenging, especially for newly listed companies or markets with limited data availability.
5) Behavioral Biases: Investor behavior, driven by emotions such as fear and greed, can lead to irrational market movements and distort stock prices. Behavioral biases, such as herding behavior or overreaction to news, can challenge the accuracy of analysis based on rational market assumptions.
6) Regulatory Changes: Stock markets are subject to regulatory changes and interventions by regulatory bodies. Changes in regulations or policies can impact stock prices, trading volumes, and market dynamics, making it necessary to stay updated and adapt the analysis accordingly.
7) Black Swan Events: Unexpected and rare events, often referred to as "Black Swan" events, can have a significant impact on the stock market. These events, such as financial crises or natural disasters, are challenging to predict and can disrupt traditional market analysis models. 
8) Time Sensitivity: Stock market analysis often requires real-time or near-real-time data to capture the most current market conditions. Delayed or outdated data can impact the accuracy and relevance of the analysis.

![20](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/444b898a-3bea-4d92-8258-f3064148d5e0)


# Objective
1) The project involves analyzing financial market data, specifically focusing on OHLC (Open, High, Low, Close) prices of stocks.
![1](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/698a35ab-0077-488d-b2a3-83822eefea83)

2) The solution supports multiple tickers by accepting a list of ticker symbols and fetching data for each ticker.
![2](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/7c91a83e-0076-4255-bb1a-a388cfd0e2b1)

3) The project allows fetching minute-level data with customizable time periods and intervals.
4) Fundamental data for specific stocks can be obtained, providing essential information about the company's financial health.
5) Balance sheets of individual stocks can be retrieved, offering insights into their financial position.
6) Various financial metrics like PB ratio, PE ratio, and more can be fetched for analysis.

7) The project provides volumes data for each stock, representing the number of shares traded.
![3](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/a5d7d15f-325b-45ae-9a7e-a06d807d5a4d)

8) The solution includes functionality to locate volume spikes for a particular stock, visualizing them on a graph (example: HDFC Bank).
![4](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/80a26936-46c0-484d-834c-f96f34a80da4)

9) The total capital traded in the market can be calculated, indicating the overall market activity.

10) A volume chart representing the total capital traded can be plotted, illustrating market trends.
![5](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/45715304-072f-4800-b1a0-25d809d81766)

11) Moving averages can be calculated and plotted for specific stocks (example: HCL Tech, TCS), aiding in trend analysis.
![8](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/98064276-ed5b-4706-b59d-50aa067887f3)

![9](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/bad6d665-06c7-4bd5-bbcd-abeb52a08201)

12) Correlation and scatter matrix between stocks can be generated, highlighting relationships and dependencies.
![10](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/6b7ce275-7b6d-4cf6-88e8-35f3c320837b)

13) Candlestick patterns of a particular stock within a specified time period can be plotted, assisting in technical analysis.
![11](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/e4e4e19e-5506-4047-a12a-efec0a68b645)

14) The project supports identifying daily percentage changes or volatile market conditions.
15) Histograms can be plotted to visualize the distribution of volatile values.
![12](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/f04493a9-9cfe-46e5-bc64-8940e054cfe8)

16) KDE (Kernal Density Estimate) plots can be generated to validate and analyze volatile changes in stocks.
![13](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/9bbdc4e9-93bb-4cf1-b576-568bb30a15fe)

17) Box plots can be created to validate and compare the volatility of stocks.
![14](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/b551c2f6-0d2a-459a-ad11-b931b6d8642b)

18) Volatility of multiple stocks can be compared using scatter plot matrix, facilitating analysis and pattern recognition.
![16](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/1a348b83-2d8a-40ac-a90b-80ca62fc76f8)

19) Cumulative returns of a particular stock can be calculated, offering insights into the overall performance over time.
![17](https://github.com/rahulrajan15/Stock_Analysis_EDA_Project/assets/113009011/5be58c0a-0a43-46ee-a18d-aa5c39a8c138)




