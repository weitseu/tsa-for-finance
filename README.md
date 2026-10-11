## 📂 tsa-for-finance/

- **stylized_facts_of_asset_returns.ipynb**
  - Non-normality: fat tails, skewness, kurtosis
  - Autocorrelation and weak-form efficiency (Ljung-Box)
  - Volatility clustering and ARCH effects (Engle's LM test)
  - The leverage effect
  - Cross-asset correlation and tail dependence

- **ARIMA_engine.ipynb**
  - Monthly US CPI inflation (FRED)
  - Unit roots and stationarity
  - Order identification from the ACF and PACF, selection by AIC/BIC
  - Residual diagnostics
  - Parameter instability under regime change

- **volatility_modeling.ipynb**
  - GARCH(1,1): persistence, half-life, and the long-run variance
  - Standardized residuals
  - Asymmetric models (EGARCH, GJR-GARCH)
  - Out-of-sample forecasts
  - Value at Risk

- **multivariate_time_series.ipynb**
  - VAR models, lag selection, and Granger causality
  - Impulse responses and the identification problem
  - Cointegration (Engle-Granger) and pairs trading
  - Principal component analysis: the market factor