# SPY Stock Price Prediction Using LSTM & GRU
This project predicts the next-day closing price of SPY (S&P 500 ETF) using deep learning models. It applies LSTM and GRU neural networks to capture time-based dependencies in 14 years of historical stock data (2011–2025).

## ML Models
### Long Short-Term Memory (LSTM)
LSTMs are a type of Recurrent Neural Network (RNN) that are particularly well-suited for time series forecasting because they can learn long-term dependencies. The model architecture includes two LSTM layers each followed by dropout layers to prevent overfitting, and a final Dense layer for regression output.
### Gated Recurrent Unit (GRU)
GRUs are a streamlined variant of LSTMs with fewer parameters and gates, which often leads to faster training and potentially similar performance. Like the LSTM model, this GRU model uses two GRU layers with dropout and a Dense output layer to predict the next adjusted closing price
## Files
- `notebooks/`: Jupyter notebook
- `images/`: Model result plots
- `data/`: Training set and test set

## GitHub Repo

https://github.com/jinjwangca/deep-learning
