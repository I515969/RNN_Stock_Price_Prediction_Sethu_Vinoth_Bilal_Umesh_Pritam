# RNN Stock Price Prediction

## Table of Contents

- [Problem Statement](#problem-statement)
- [Business Goal](#business-goal)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)

---

## Problem Statement

The dataset consists of historical stock price data for four technology companies — **Amazon (AMZN)**, **Google (GOOGL)**, **IBM (IBM)**, and **Microsoft (MSFT)** — covering the period from January 2006 to January 2018. Each CSV file contains daily records of Open, High, Low, Close prices and trading Volume for the respective company.

The challenge is to build Recurrent Neural Network (RNN) models — including Vanilla RNN, Stacked LSTM, and Stacked GRU — that can accurately predict the closing stock prices of all four companies given a sequence of historical price data over a 63-day window.

> *"Given the stock prices of Amazon, Google, IBM, and Microsoft for a set number of days, predict the stock price of these companies after that window."*

---

## Business Goal

The objective of this project is to leverage sequential deep learning architectures to model and predict stock price movements across four major technology companies. Using data from all four companies simultaneously allows the model to capture broader market sentiment and sector-wide trends.

Key goals:

- Predict the closing stock prices of AMZN, GOOGL, IBM, and MSFT using a 63-day historical window
- Compare the performance of Vanilla RNN, Stacked LSTM, and Stacked GRU architectures
- Apply proper data preprocessing including global MinMaxScaling on training data only to prevent data leakage
- Tune hyperparameters including units, dropout, optimizer, learning rate, and batch size to find the optimal model configuration
- Use Early Stopping to prevent overfitting and restore the best model weights

---

## Technologies Used

| Library       | Version |
|---------------|---------|
| Python        | 3.12    |
| NumPy         | 2.4.6   |
| Pandas        | 3.0.3   |
| Matplotlib    | 3.10.0  |
| Seaborn       | 0.13.2  |
| TensorFlow    | 2.21.0  |
| Keras         | 3.x     |
| scikit-learn  | 1.9.0   |

---

## Acknowledgements

This project was completed as part of an RNN assignment for an AI and ML course offered by IIITB through Upgrad.

---

## Contact

For inquiries, reach out to the project creator at [pritam.saha@sap.com](mailto:pritam.saha@sap.com).
