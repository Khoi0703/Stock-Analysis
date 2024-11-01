# Stock Market Analysis - VN30 Index

This Jupyter Notebook provides an analysis of the VN30 index, which comprises the 30 largest-cap stocks on the Ho Chi Minh Stock Exchange (HOSE) in Vietnam. The aim of this project is to explore and analyze stock data, focusing on buy prices, sell prices, and transaction volumes to gain insights into market behavior.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Preparation](#data-preparation)
3. [Data Analysis](#data-analysis)
4. [Feature Engineering](#feature-engineering)
5. [Modeling](#modeling)
6. [Results](#results)
7. [Future Work](#future-work)
8. [References](#references)

---

### 1. Introduction

The VN30 index serves as a key indicator of market performance in Vietnam. This project addresses the challenges of analyzing high-frequency stock data and explores potential methods for forecasting price movements. 

### 2. Data Preparation

- **Data Import**: We load and prepare a dataset of stock transaction records, reversed to sort from the oldest to the most recent date.
- **Data Summary**: The dataset includes buy prices, sell prices, and transaction volumes for 30 companies in the VN30 group.
- **Preprocessing**: We ensure the dataset contains no null values or duplicates.

### 3. Data Analysis

The data is divided by stock attributes such as buy price, sell price, and volumes, allowing for focused analysis. Key insights include:
- The distribution of transaction volumes throughout the trading day.
- Cash flow analysis through the calculation of total buy and sell values.

### 4. Feature Engineering

We conduct feature engineering to:
- Identify the most active trading times.
- Calculate average prices and transaction volumes to improve prediction models.

### 5. Modeling

The notebook employs various machine learning and deep learning models, such as:
- **Linear Regression** for basic prediction.
- **LSTM Networks** for time series prediction, leveraging TensorFlow and Keras.

### 6. Results

Model performance is evaluated based on Mean Squared Error, Mean Absolute Error, and R² Score. We analyze the predictive power of different models and compare them to assess the most effective approach for forecasting VN30 stock movements.

### 7. Future Work

Potential improvements include:
- Expanding the dataset to include additional market factors.
- Testing additional machine learning models for better predictive accuracy.
