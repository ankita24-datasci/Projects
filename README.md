# Stock Price Prediction with Sentiment Analysis and Random Forest

This project leverages **Reddit sentiment analysis** and **historical stock price data** to predict stock price movements (up or down) using a **Random Forest Classifier**. The workflow integrates Natural Language Processing (NLP), financial data analysis, and machine learning techniques.

---

## Features
- **Data Collection**:
  - Reddit posts from `r/wallstreetbets` related to stock predictions.
  - Historical stock price data using the `yfinance` library.
  
- **Text Processing**:
  - Extracts and vectorizes text data using **TF-IDF**.
  - Sentiment analysis using **VADER Sentiment Analyzer**.

- **Machine Learning**:
  - Combines sentiment scores and TF-IDF features for model training.
  - Uses **Random Forest** with hyperparameter tuning for classification.
  - Evaluates the model with cross-validation and test data.

---

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- pip

### Required Libraries
Install the dependencies using:
```bash
pip install -r requirements.txt
praw
yfinance
scikit-learn
vaderSentiment
numpy
pandas
matplotlib
seaborn
