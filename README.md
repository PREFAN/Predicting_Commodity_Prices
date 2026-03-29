# Predicting_Commodity_Prices
Project Overview

Price fluctuation in agricultural commodities such as cocoa continues to be a major issue affecting producers, exporters, importers, investors, and other stakeholders in the global commodity market. Because billions of dollars move through the cocoa value chain each year, the ability to forecast cocoa prices accurately is important for informed financial, production, and investment decisions.

This project focuses on forecasting the future price trend of cocoa using Python-based statistical and time series techniques. Cocoa price forecasting is challenging because price movement is not driven only by historical patterns; it is also influenced by external economic and environmental factors such as weather conditions, climate change, inflation, supply chain disruptions, plant diseases, and production yield.

To address this complexity, this study uses computerized forecasting methods rather than relying solely on traditional historical or econometric approaches. The project applies exploratory data analysis, statistical testing, time series transformation, ARIMA forecasting, Bollinger Bands, and Relative Strength Index (RSI) to analyze cocoa price behavior and predict future market movement.

The results of this project show that cocoa prices are highly volatile and are likely to continue experiencing both upward and downward fluctuations, driven by external pressures in the global commodity environment.

Problem Statement

Forecasting cocoa prices is a complex task because the commodity market is highly sensitive to several unpredictable factors. Analysts cannot depend only on previous historical prices or conventional econometric models to accurately predict future cocoa price behavior.

Cocoa prices are affected by:

Weather and seasonal conditions
Climate change
Inflation
Global supply chain disruptions
Plant diseases affecting cocoa farms
Production yield changes
Market speculation and international demand

Because of these uncertainties, there is a need for more advanced Python-based forecasting models that can better capture volatility and improve price trend prediction.

Project Objectives

The main objectives of this project are to:

Analyze historical cocoa futures price data
Explore cocoa price behavior using descriptive statistics and visualization
Identify patterns, trends, and volatility in cocoa prices
Test whether the cocoa price time series is stationary
Transform non-stationary data into a stationary series
Build a time series forecasting model using ARIMA
Use Bollinger Bands and RSI to assess volatility and momentum
Forecast future cocoa price trends
Provide insight into how cocoa prices may behave under continued market uncertainty
Dataset Information

This project uses historical cocoa futures data obtained from Yahoo Finance.

Dataset Details
Commodity: Cocoa Futures (CC=F)
Source: Yahoo Finance
Time Period: Historical daily price data
Variables Included:
Date
Open
High
Low
Close
Adjusted Close
Volume

The dataset provides sufficient time-based information for conducting both exploratory analysis and time series forecasting.

Tools and Technologies Used

This project was built using the following Python tools and libraries:

Programming Language
Python
Libraries
Pandas – data loading, cleaning, and manipulation
NumPy – numerical operations
Matplotlib – data visualization
Seaborn – enhanced statistical visualization
SciPy – statistical testing
Statsmodels – time series analysis and ARIMA modeling
Methodology

The project follows a structured workflow to analyze and forecast cocoa prices.

1. Data Collection and Preparation
Imported historical cocoa futures data
Inspected dataset structure
Checked for missing values and data consistency
Converted date columns for time series analysis
2. Exploratory Data Analysis (EDA)

To understand the behavior of cocoa prices, the following visual and statistical techniques were used:

Summary statistics
Line plots
Histograms
Box plots
Scatter plots
Correlation matrix

EDA helped identify:

Overall price movement
Volatility
Distribution patterns
Outliers
Relationships among variables
3. Statistical Analysis

Statistical tests were conducted to understand whether price differences were significant and whether price movement followed a predictable structure.

Tests included:

One-sample t-test
Two-sample t-test
Paired t-test
One-way ANOVA
4. Time Series Analysis

Because cocoa prices change over time, time series methods were used to prepare the data for forecasting.

This involved:

Plotting the original time series
Detecting trend and volatility
Applying log transformation to stabilize variance
Applying first differencing to remove trend
Performing the Augmented Dickey-Fuller (ADF) test
Examining ACF and PACF plots
5. Forecasting Model

After achieving stationarity, an ARIMA (0,1,1) model was fitted to the cocoa price series.

The ARIMA model was used to:

Capture historical dependency in price movement
Forecast future cocoa prices
Evaluate the likely short-term trend of cocoa prices
6. Technical Indicators

To complement the ARIMA model and improve interpretation of market conditions, two technical indicators were used:

Bollinger Bands – to assess volatility and possible overbought/oversold zones
Relative Strength Index (RSI) – to evaluate momentum and potential reversal points
Key Analyses Performed

This project includes the following major analyses:

Exploratory Data Analysis
Descriptive statistics
Price distribution analysis
Trend visualization
Volatility inspection
Outlier detection
Correlation analysis
Statistical Testing
Hypothesis testing using t-tests and ANOVA
Interpretation of price variability and significance
Time Series Diagnostics
Stationarity testing
Log transformation
Differencing
ACF/PACF interpretation
Residual analysis
Forecasting
ARIMA model fitting
Price prediction
Forecast visualization
Residual diagnostics
Technical Indicator Analysis
Bollinger Band positioning
RSI movement
Momentum and volatility interpretation
Model Used
ARIMA (0,1,1)

The primary forecasting model used in this project is:

ARIMA (0,1,1)

This model was selected after transforming the original cocoa price series into a stationary series using first differencing.

Why ARIMA?

ARIMA is a widely used time series forecasting model because it:

Handles historical sequential data effectively
Works well for univariate forecasting
Can model trends after differencing
Is interpretable and suitable for short-term commodity forecasting
Key Findings

The project produced several important insights about cocoa price behavior:

Cocoa prices are highly volatile
The price series shows significant upward and downward movement
The original cocoa price data is non-stationary
Log transformation helps stabilize variance but does not fully remove trend
First differencing successfully converts the series into a stationary time series
The ARIMA (0,1,1) model is suitable for short-term forecasting
Bollinger Bands show repeated periods of high volatility and possible overbought conditions
RSI indicates strong momentum at certain periods, suggesting potential corrections
Cocoa prices are likely to continue fluctuating due to persistent global economic and environmental pressures
Conclusion

This project demonstrates that forecasting cocoa prices requires more than simply looking at historical price trends. Cocoa is influenced by a wide range of external economic, environmental, and market-related factors, making it a complex commodity to predict.

By using Python-based statistical analysis and time series forecasting techniques, this study shows that cocoa prices are expected to continue experiencing frequent fluctuations, with both upward and downward movements likely in the future.
