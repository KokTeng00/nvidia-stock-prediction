# Nvidia Stock Price Prediction

This project aims to predict Nvidia's stock prices using different machine learning and deep learning models. The project includes data visualization, data preprocessing, model training, model evaluation, and prediction.

## Dataset

The dataset used in this project is Nvidia's stock price data from 2000 to 2024, which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/prajwaldongre/nvidia-corp-share-price-2000-2024).

## Requirements

- Python 3
- PyTorch
- Optuna
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Models

- Linear Regression Model
- LSTM Model

## Usage

1. Load the Nvidia stock price dataset.
2. Preprocess the data.
3. Train the Linear Regression model.
4. Evaluate the Linear Regression model.
5. Train the LSTM model with hyperparameter tuning using Optuna.
6. Evaluate the LSTM model.
7. Make predictions using the trained models.

## Results

The LSTM model was able to capture the general trends and patterns in the data. The predicted prices are following a similar trend to the actual prices.

## Future Enhancements

- Try different hyperparameters to improve the model's performance.
- Experiment with different architectures, such as using a bidirectional LSTM or adding dropout layers to prevent overfitting.
- Explore other features or technical indicators that could potentially improve the model's predictive power.

## License

This project is licensed under the terms of the MIT license.
