# Stock-Market-Analysis

A **Streamlit** web application that predicts future stock prices using a deep learning model built with **TensorFlow/Keras**. The app downloads historical stock data via the **Yahoo Finance API**, processes it, and visualizes moving averages along with predicted stock prices.

---

## Features

- Download and display historical stock price data for any ticker symbol (default: GOOG).
- Calculate and plot moving averages for 100, 200, and 250 days.
- Predict future closing prices using a pre-trained LSTM deep learning model.
- Visualize original vs. predicted stock prices on interactive charts.
- Simple and intuitive user interface using Streamlit.

---

## Technologies Used

- Python 3.x  
- [Streamlit](https://streamlit.io/)  
- [TensorFlow/Keras](https://www.tensorflow.org/)  
- [Yahoo Finance (`yfinance`)](https://pypi.org/project/yfinance/)  
- [scikit-learn](https://scikit-learn.org/stable/) (for MinMaxScaler)  
- [Matplotlib](https://matplotlib.org/)  
- [Pandas](https://pandas.pydata.org/) and [NumPy](https://numpy.org/)
