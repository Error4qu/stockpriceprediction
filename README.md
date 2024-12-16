## Stock Price Prediction Using ARIMA and LSTM Models with Twitter Sentiment Analysis

**This project** aims to predict stock prices using two machine learning models (ARIMA and LSTM) while incorporating **Twitter sentiment analysis** to improve predictions.

**Key Features:**

* **Stock Price Prediction:**
    * **ARIMA model:** Forecasts future prices based on historical data.
    * **LSTM model:** Captures complex patterns using time-series prediction.
* **Sentiment Analysis:**
    * Analyzes recent tweets to gauge public sentiment towards a stock (using TextBlob).

**Data Sources:**

* Stock data: Yahoo Finance (yfinance API).
* Social media sentiment: Twitter API.

**Dependencies:**

* `yfinance`: Fetch historical stock data.
* `tweepy`: Interact with the Twitter API.
* `textblob`: Perform sentiment analysis on tweets.
* `matplotlib`: Create visualizations.
* `keras`: Build and train the LSTM model.
* `pmdarima`: Implement ARIMA with auto-parameter tuning.
* `scikit-learn`: Preprocess and split data.

**Installation:**

```bash
pip install yfinance tweepy textblob matplotlib keras pmdarima scikit-learn
