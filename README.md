# Stock Prediction App

## Overview

The Stock Prediction App is a web application designed to predict the future price of a selected stock using historical data. The app leverages **Streamlit** for the user interface and **Facebook Prophet** for time series forecasting. This project is intended for anyone interested in financial data analysis and predictive modeling.

## Features

- **Interactive User Interface**: Streamlit allows users to interact with the app by selecting stocks, date ranges, and prediction horizons.
- **Stock Data Retrieval**: The app fetches historical stock price data from financial APIs (such as Yahoo Finance).
- **Predictive Modeling**: Uses Facebook's Prophet model to predict future stock prices.
- **Visualization**: Displays historical and predicted stock prices using dynamic plots.

## Technology Stack

- **Python**: The core programming language used for the app.
- **Streamlit**: A Python library used to create the web interface.
- **Prophet**: A time series forecasting tool developed by Facebook.
- **Pandas**: Used for data manipulation and preparation.
- **Plotly/Matplotlib**: For creating interactive and static visualizations.
- **Yahoo Finance Library**: For fetching historical stock data.

## Installation
- **numpy**
- **streamlit**
- **plotly**
- **pandas**
- **chart_studio**
- **prophet**
- **yfinance**
### Prerequisites

- Python 3.7 or later
- pip (Python package manager)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/stock-prediction-app.git
   cd stock-prediction-app
