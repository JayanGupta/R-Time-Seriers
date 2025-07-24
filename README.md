# Time Series Forecasting in R

This repository contains two notebooks where I’ve explored time series forecasting using **R**. The goal was to better understand classical forecasting techniques like AR, MA, ARIMA, and exponential smoothing, along with basic model evaluation.

These notebooks are part of my self-study and practice — they’re not tied to a specific project or dataset.

## Notebooks

- **forecasting_in_R.ipynb**  
  Covers multiple forecasting techniques using built-in R datasets like `AirPassengers`, `Nile`, and `nottem`. Includes decomposition, smoothing, ARIMA modeling, and evaluation.

- **Temperature_AR_Model.ipynb**  
  Focuses on autoregressive modeling (AR) for temperature data. Includes data preprocessing, stationarity checks, lag selection, model fitting, and performance metrics.

## Packages Used

The notebooks use the following R packages:

- `forecast`
- `tseries`
- `ggplot2`
- `zoo`
- `lubridate`

## How to Run ?

Make sure you have R installed and set up to run in Jupyter notebooks. You’ll also need the following packages:

```r
install.packages(c("forecast", "tseries", "ggplot2", "zoo", "lubridate"))
