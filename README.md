# Apple Stock Price Forecasting with ARIMA

<img align="center" alt="Coding" width="400" src="https://qph.cf2.quoracdn.net/main-qimg-dbf50fd06d454dca02477f637b2fba73">

This project aims to predict future stock prices of Apple using the ARIMA (AutoRegressive Integrated Moving Average) model. It comprises an exploratory analysis phase where historical data is examined, followed by the construction of the ARIMA model for forecasting. The final section evaluates the model's accuracy in predicting Apple's stock prices against actual values. Explore the analysis to gain insights into Apple's stock trends and the efficacy of ARIMA modeling for forecasting.

The methodology employed in this project can be adapted and applied to analyze the performance of other stocks or even cryptocurrencies with minor adjustments.

# Dataset
Data was extracted using the YFinance library.

# Summary
### Chapter 1: Exploratory Analysis
- 1.1: Importing Data and First Look: Loading historical data of Apple stocks and preliminary analysis.
- 1.2: Visualization of Apple Stocks Price History in USD: Graphs to visualize the historical trajectory of Apple stock prices in USD.
### Chapter 2: Building ARIMA Model
- 2.1: Splitting Data: Splitting data into training and testing sets.
- 2.2: Time Series Forecasting with ARIMA Model: Implementation of the ARIMA model to predict future Apple stock prices.
### Chapter 3: Conclusion
- 3.1: Apple Stocks Price Prediction Comparison: Predicted Value vs. Actual Value.
- 3.2: MAE (Mean Absolute Error): Metric to evaluate the model's accuracy.
- 3.3: MAPE (Mean Absolute Percentage Error): Metric to evaluate the model's accuracy in percentage terms.
- 3.4: RMSE (Root Mean Squared Error): Metric to evaluate the model's accuracy, penalizing larger errors.

# Libraries Used
- yfinance
- numpy
- matplotlib
- statsmodels.api
- sklearn

# Contributions
Contributions are welcome! If you find any issues or have suggestions to improve this project, feel free to open an issue or submit a pull request.

# Author
Julio Cesar Yamashita Martins - Developer and Data Scientist

# E-mail
yamashitajulio@gmail.com
