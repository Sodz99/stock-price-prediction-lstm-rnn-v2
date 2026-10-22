# Stock Price Prediction using RNN and LSTM

The aim of this project is to develop a robust stock price prediction system utilizing recurrent neural networks (RNN) and long short-term memory (LSTM) networks.

## Overview
Stock price prediction plays a crucial role in financial markets, and accurate forecasts can have significant implications for businesses, investors, and financial institutions.

Stock price prediction helps investors and fund managers make informed investment decisions. By accurately forecasting future stock prices, investors can identify potential opportunities for maximizing profits or minimizing losses. It enables them to allocate their capital wisely and adjust their investment portfolios based on predicted price movements.

Machine and Deep Learning have demonstrated their potential to enhance stock price prediction accuracy and assist investors, traders, and financial analysts in making informed decisions. By leveraging ML techniques, businesses can gain valuable insights, optimize investment strategies, and improve risk management in stock market's complex and dynamic realm.

## Data
The dataset used for this project consists of historical stock prices for Apple Inc. (AAPL) obtained from the Yahoo Finance API. It includes a comprehensive record of daily stock price data, capturing the opening, closing, highest, and lowest prices, as well as the trading volume for each trading day.

_Data is not included in this repository._

## Approach
- Neural Networks Basics: ○ Review the basics of neural networks to understand their structure and functionality. ○ Building and Training Neural Networks with Keras on an Example Dataset
- Loading Time Series Data: ○ Obtain the time series data for stock prices from yahoo finance.
- Data Transformations: ○ Perform feature scaling or normalization to bring data into a consistent range. ○ Overlapping window creation for training.
- Recurrent Neural Networks: ○ Model Building and Training ○ Sequence Generation and Evaluation
- LSTMs: ○ Model Building and Training

○ Sequence Generation and Evaluation

- Multivariate Input and LSTMs ○ Creating Technical Indicators ○ Creating Labels ○ Perform feature scaling or normalization to bring data into a consistent range. ○ Model Building and Training ○ Evaluation

Modular code overview:

Once you unzip the modular_code.zip file, you can find the following folders.

1. lib
2. ml_pipeline
3. engine.py
4. output
5. requirements.txt
6. readme.md
1. The lib folder is a reference folder and contains the original ipython notebook as in the lectures.
2. The ml_pipeline folder contains all the functions put into different python files, which are appropriately named. The engine.py script then calls these python functions to run the steps in one go to train the model and print the results.
3. The output folder contains the saved models from engine.py.
4. The requirements.txt file has all the required libraries with respective versions. Kindly install the file using the command pip install -r requirements.txt
5. All the instructions for running the code are present in readme.md file

## Tech stack
➔ Language: Python ➔ Libraries: keras, tensorflow, statsmodels, numpy, pandas, yfinance, pandas datareader, pandas_ta

## How to run
```bash
pip install -r modular_code/requirements.txt
python modular_code/engine.py
python modular_code/ml_pipeline/train.py
```
Notebooks: [`lstm_p1.ipynb`](modular_code/lib/lstm_p1.ipynb)

## Project structure
```
.gitignore
README.md
modular_code/
  engine.py
  lib/
    lstm_p1.ipynb
  ml_pipeline/
    train.py
    utils.py
  readme.md
  requirements.txt
```

## Credits
Based on a ProjectPro guided project.
