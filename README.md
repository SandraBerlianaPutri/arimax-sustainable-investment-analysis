# ARIMAX Analysis for Sustainable Investment

## About
This project explores time series models for three asset series using historical asset data and macroeconomic indicators. ARIMA models are developed as a foundation before incorporating external predictors to investigate their potential contribution to asset modeling and forecasting.

The project was prepared for **Ajang Pengenalan Statistika dan Festival Data (ANAVA) 2025**, organized by Gadjah Mada University. The team advanced to the **semifinalist** stage.

## Project Files
- [Access Project Files on Google Drive](https://drive.google.com/drive/folders/1JSdrIDspVzoEqcI15zXX3ho4p9JTnBxw?usp=sharing)

## Dataset
- **Macroeconomic predictors:**
  - `exchange_rate`: Exchange rate
  - `gdp_growth`: GDP growth
  - `inflation_rate`: Inflation rate
  - `trade_diff`: Trade-related indicator
  - `unemployment_rate`: Unemployment rate
- **Data structure:** Time series observations for three assets, paired with five macroeconomic indicators.

## Methods
- **Exploratory Data Analysis:** Examined relationships among asset series and macroeconomic indicators using scatterplot matrices and time series plots.
- **Stationarity Testing:** Applied the Augmented Dickey–Fuller test and differencing where needed.
- **Model Identification:** Used ACF and PACF plots to guide ARIMA order selection.
- **ARIMA Modeling:** Evaluated candidate specifications for the three asset series.
- **ARIMAX Modeling:** Incorporated five macroeconomic indicators as external regressors.
- **Residual Diagnostics:** Examined residual normality, fitted-value patterns, serial correlation, and residual behavior over time.
- **Forecasting:** Generated forecasts using fitted models and corresponding future values of the external predictors.

## Achievement
**Semifinalist — ANAVA 2025**  
Ajang Pengenalan Statistika dan Festival Data, Gadjah Mada University.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
