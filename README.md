
# Notebook Sections

## 1. Loading and Cleaning the Dataset

The dataset (`Minitab (1) (1).csv`) is loaded using pandas. The date column is converted to datetime and set as the index. NaN values are dropped for cleanliness.

## 2. Exploratory Data Analysis (EDA)

This section provides a visual representation of the fuel prices in Nigeria over the years. It includes an Augmented Dickey-Fuller Test to check for stationarity.

## 3. Time Series Analysis

First and second-order differencing are applied to achieve stationarity. The best parameters for the ARIMA model are identified using `auto_arima` from the `pmdarima` library.

## 4. ARIMA Model Fitting and Forecasting

The ARIMA model is trained with the differenced data, and fuel prices are forecasted for the next 7 years (2024-2030).

# Results

The forecasted fuel prices are presented with a plot for easy visualization.

# Usage

1. Open the Jupyter Notebook (`FuelPriceARIMA.ipynb`) in your preferred environment.
2. Follow the sections sequentially for data loading, analysis, and forecasting.
3. Make sure to install the required libraries mentioned above.
4. Feel free to experiment with the notebook and contribute to further improvements!

*Note: This summary provides an overview. Refer to the notebook for detailed code and analysis.*
