# Nvidia Stock Price Prediction

This project aims to predict Nvidia's stock prices using different techniques such as Linear Regression and LSTM (Long Short-Term Memory) networks.

## Project Structure

The project mainly consists of a Jupyter notebook `nvidia_stock_price.ipynb` which contains all the code and visualizations.

## Libraries Used

- numpy
- pandas
- matplotlib
- mpl_finance
- sklearn
- torch
- optuna

## Data

The data used in this project is Nvidia's stock price data, which includes the date, open price, high price, low price, close price, and volume.

## Models

Two models are used in this project:

1. **Linear Regression Model**: This model uses the date, close price, volume, and 10-day and 50-day moving averages to predict the close price.

2. **LSTM Model**: This model uses an LSTM network to predict the close price. The LSTM network is trained using Optuna for hyperparameter optimization.

## Results

The results of the models are visualized in the Jupyter notebook. The predicted prices are compared with the actual prices and moving averages.

## Usage

To run the project, open the `nvidia_stock_price.ipynb` notebook in a Jupyter environment.

## License

This project is open source, under the terms of the [MIT License](https://opensource.org/licenses/MIT).
