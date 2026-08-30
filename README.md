# 📈 Reliance Stock Price Prediction

A machine learning project that estimates the next trading day's closing price of Reliance Industries using historical stock market data.

## 📌 Project Overview

This project uses historical stock price data of Reliance Industries (`RELIANCE.NS`) and machine learning techniques to estimate the next trading day's closing price.

The project compares multiple regression models and selects the better-performing model based on evaluation metrics.

## 🎯 Objectives

- Collect historical Reliance stock market data.
- Perform data exploration and visualization.
- Create useful features from historical stock data.
- Train machine learning regression models.
- Compare model performance.
- Select the best-performing model.
- Provide a simple interface for making predictions.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance
- Joblib
- Gradio
- Google Colab

## 🤖 Machine Learning Models

### 1. Linear Regression
Used as a simple baseline regression model for predicting stock prices.

### 2. Random Forest Regression
Used to capture more complex relationships between the input features and the target price.

## 📊 Evaluation Metrics

The models are evaluated using:

- **MAE** — Mean Absolute Error
- **RMSE** — Root Mean Squared Error
- **R² Score** — Coefficient of Determination

## 🔄 Project Workflow

```text
Historical Stock Data
        ↓
Data Exploration
        ↓
Data Preprocessing
        ↓
Feature Engineering
        ↓
Train/Test Split
        ↓
Machine Learning Models
        ↓
Model Evaluation
        ↓
Best Model Selection
        ↓
Next-Day Price Prediction
        ↓
Gradio Interface
