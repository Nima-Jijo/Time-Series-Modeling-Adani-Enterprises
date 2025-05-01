# Time Series Modeling: Adani Enterprises

This project performs an end-to-end time series analysis on daily stock price data of **Adani Enterprises**, using classical statistical methods in **R**. The analysis includes decomposition, stationarity checks, transformations, and forecasting using models like ARIMA.

## Key Features

- Imported stock data directly from Google Sheets
- Log transformation and differencing for stationarity
- Time series decomposition into trend, seasonal, and residual components
- ADF and KPSS tests to check for stationarity
- Forecasting using the `forecast` package (ARIMA models)
- Visualization using `ggplot2` and base R plots

##  Tools and Packages Used

- `googlesheets4` – to read data from Google Sheets
- `forecast`, `tseries`, `seastests` – for time series analysis
- `ggplot2`, `gridExtra` – for plotting
- `xts`, `zoo`, `quantmod` – for handling time-series objects
- `dplyr` – for data wrangling
- `Metrics` – for evaluating model performance

## How to Run

1. Open the `.ipynb` file using R Jupyter Notebook or RStudio with the IRkernel installed.
2. Make sure all required packages are installed (see top of the notebook).
3. Execute each cell in sequence to load data, preprocess, model, and forecast.

## File Structure

- `adani_enterprises.ipynb` – Main notebook containing code, plots, and outputs.

##  License

This project is for educational purposes and not intended as financial advice.

---

*Created by Nima Jijo as part of a data science learning initiative.*
