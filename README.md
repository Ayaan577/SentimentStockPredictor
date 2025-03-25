# SentimentStockPredictor
## Overview
A hybrid ML framework combining sentiment analysis and deep learning models to predict stock prices. Using Twitter for sentiment data, LSTM models for time-series forecasting, and GANs for enhanced prediction accuracy.

## Features
- **Sentiment Analysis**: Processes Twitter data using NLTK's VADER to extract sentiment scores (positive, neutral, negative, and compound).  
- **Technical Indicators**: Computes moving averages, Bollinger Bands, MACD, and more for financial analysis.  
- **LSTM Model**: Predicts stock prices using historical data and sentiment features.  
- **GAN Integration**: Enhances predictions by generating synthetic data to improve model robustness.  
- **Performance Evaluation**: Metrics include RMSE, MAE, MAPE, and R² Score.

---

## Frameworks and Tools
- **Programming Language**: Python  
- **Deep Learning**: TensorFlow, Keras  
- **Sentiment Analysis**: NLTK VADER  
- **Data Visualization**: Matplotlib, Seaborn  
- **Data Handling**: Pandas, NumPy, Scikit-learn

---
## Results

- Achieved RMSE: **0.0926** on test data with LSTM-GAN integration.

- Visualized actual vs. predicted stock prices for comprehensive evaluation.

---
