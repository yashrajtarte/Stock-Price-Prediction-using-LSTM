# Stock Price Prediction using LSTM

This repository contains code for predicting stock prices using a Long Short-Term Memory (LSTM) neural network. The code is written in Python and utilizes the TensorFlow and Keras libraries.

## Overview

Stock price prediction is a challenging task in the field of financial forecasting. The goal of this project is to develop a model that can accurately predict future stock prices based on historical data. The LSTM architecture is chosen for its ability to capture long-term dependencies in sequential data, making it suitable for time series prediction tasks like stock price forecasting.

The repository provides the following files:

- `stock_prediction_lstm.ipynb`: Jupyter Notebook containing the code for data preprocessing, model building, training, evaluation, and prediction.
- `Tesla.csv`: Historical stock price data for Tesla (example dataset).
- `model_weights.h5`: Saved weights of the trained LSTM model.

## Dependencies

The code requires the following dependencies:

- Python 3.x
- TensorFlow
- Keras
- matplotlib
- pandas
- pandas_datareader
- scikit-learn

You can install the dependencies using pip:

```
pip install tensorflow keras matplotlib pandas pandas_datareader scikit-learn
```

## Usage

To use the code, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/stock-price-prediction-lstm.git
```

2. Navigate to the project directory:

```
cd stock-price-prediction-lstm
```

3. Ensure that you have the historical stock price data in a CSV file named `Tesla.csv` (or replace it with your desired stock dataset). Place the CSV file in the same directory as the Jupyter Notebook.

4. Open the `stock_prediction_lstm.ipynb` file in Jupyter Notebook or JupyterLab.

5. Run the code cells in the Notebook sequentially to perform data preprocessing, build the LSTM model, train the model, evaluate its performance, and make predictions.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as per the license terms.

## Contributing

Contributions to this repository are welcome. If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

## Acknowledgments

- This project is inspired by the works on stock price prediction using LSTM networks in the field of financial forecasting.
- The example dataset used in this project is sourced from [Yahoo Finance](https://finance.yahoo.com/).
