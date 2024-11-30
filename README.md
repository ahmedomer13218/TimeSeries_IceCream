# Time Series Analysis: Ice Cream Dataset 🍦

This repository showcases the process of **Time Series Analysis** using the **Ice Cream Consumption Dataset**. The project applies both **statistical models** and **deep learning techniques** to analyze trends, check for stationarity, and forecast future values.

## Table of Contents  
- Overview  
- Dataset  
- Key Features  
- Project Structure  
- Installation  
- Usage  
- Contributing  
- License  

## Overview  
This project walks through the process of analyzing ice cream consumption data using both **statistical models** and **deep learning**. The project covers:  
1. **Stationarity Testing**: Identifying whether the data is stationary or non-stationary using various methods.
2. **Statistical Models**:  
   - **ARMA** and **ARIMA** for model fitting and forecasting.  
   - Exploring advanced models like **SARMA**, **GARCH**, and **ETS**.
3. **Deep Learning Models**: Implementing **LSTM** and **GRU** for sequence forecasting and comparing their performance.

## Dataset  
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/atharvaarya25/ice-cream-production-over-50-years). It contains time series data for ice cream consumption, which is used to build the forecasting models.

## Key Features  
1. **Stationarity Testing**:  
   - Visual Analysis, Rolling Mean/Variance, ADF Test, and KPSS Test.
2. **ARMA & ARIMA Models**:  
   - Differencing to make the data stationary.
   - Using ACF/PACF plots to determine initial values for p and q.
3. **Advanced Statistical Models**:  
   - SARMA, GARCH, and ETS models for more accurate forecasting.
4. **Deep Learning Models**:  
   - **LSTM**: Long Short-Term Memory networks to capture long-term dependencies.
   - **GRU**: Gated Recurrent Units for more efficient training and forecasting.

## Project Structure  
- [TimeSeries_IceCream.ipynb](./TimeSeries_IceCream.ipynb)  
- [LICENSE](./LICENSE)  
- [README.md](./README.md)  
- [ice_cream.csv](./ice_cream.csv)  

### Data Preprocessing  
- **Stationarity Tests**: Implemented tests to check for stationarity and transformed the data if necessary.  
- **Differencing**: Applied differencing to handle non-stationary data.
- **Model Fitting**: Used ARMA and ARIMA for model fitting based on optimal values for p, d, and q.

### Installation  
- Clone this repository:  
```bash  
git clone https://github.com/ahmedomer13218/TimeSeries_IceCream

cd TimeSeries_IceCream  
```
### Usage
Open and run the TimeSeries_IceCream.ipynb notebook.

### Contributing
We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

###
This repository demonstrates the application of both statistical and deep learning models to time series forecasting, specifically using ice cream consumption data. 🎯
