# Stock Price Prediction Using Machine Learning
Welcome to the Stock Prediction project!\
This project uses three machine learning models — Gradient Boosting Regressor (GBR), Artificial Neural Networks (ANN), and ARIMA — to predict stock prices based on real-world financial datasets.


## Project Structure
- `Stock_Prediction.ipynb` — Main Jupyter Notebook containing all code: data preprocessing, model training, evaluation, and plotting.
- `stocks.csv`, `data.csv`, `tsla_2014_2023.csv` — Input datasets.
- `README.md` — Project instructions and documentation


## Installation
Make sure you have **Python 3.8+** installed.\
Install the required libraries by running:

```bash
pip install pandas numpy scikit-learn matplotlib tensorflow statsmodels
```


## Running the Project
1. Clone or download the repository to your local machine.
2. Open the Stock_Prediction.ipynb notebook.
3. Run all cells in order:
   - Load and preprocess data
   - Encode categorical variables (Ticker, Company)
   - Normalize features
   - Train GBR, ANN, and ARIMA models
   - Evaluate performance (MSE, R²)
   - Plot actual vs predicted stock prices.


## Models Used
- **Gradient Boosting Regressor (GBR)** — for structured numerical prediction.
- **Artificial Neural Network (ANN)** — using TensorFlow/Keras for non-linear prediction.
- **ARIMA** — classical time series forecasting model.


## Evaluation Metrics
- **Mean Squared Error (MSE)**: Measures average prediction error.
- **R² Score**: Measures how well predictions fit the actual data.


## Datasets
- `stocks.csv`: Contains Open, High, Low, Close, Volume, Ticker, Date, Adj Close.
- `data.csv`: Contains Open, High, Low, Volume, Company, Date, Close/Last.
- `tsla_2014_2023.csv`: Tesla's daily stock data with technical indicators (RSI, SMA, EMA, MACD, Bollinger Bands, etc.).