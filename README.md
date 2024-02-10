# Tesla Stock Price Prediction

## Overview

This project aims to predict the closing price of Tesla stock using a Long Short-Term Memory (LSTM) model. The dataset used contains historical Tesla stock price data, and the goal is to train an LSTM model to forecast future stock prices based on past performance.


## Workflow

1. **Data Preprocessing**:
   - Import necessary libraries and read Tesla stock price data.

2. **Exploratory Data Analysis (EDA)**:
   - Plot the closing price of Tesla stock against date to understand its trends and patterns.

3. **Data Scaling and Splitting**:
   - Scale the stock price data and create training and testing datasets.

4. **Model Building**:
   - Reshape the data to meet the input requirements of the LSTM model.
   - Build an LSTM model architecture for predicting the stock prices.

5. **Model Training**:
   - Compile the LSTM model with appropriate loss function and optimizer.
   - Train the model on the training dataset, iterating over multiple epochs.

6. **Prediction and Evaluation**:
   - Use the trained LSTM model to predict Tesla stock prices on the testing dataset.
   - Calculate the root mean square error (RMSE) to evaluate the model's performance.

## Technologies Used

- Python
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, scikit-learn, Keras
- Long Short-Term Memory (LSTM) Model
