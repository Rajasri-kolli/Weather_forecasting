## Weather Forecasting
This project focuses on analyzing and forecasting global weather patterns using historical meteorological data. The objective was to explore long-term climate trends, identify seasonal patterns, and develop predictive models to forecast temperature using both statistical time-series techniques and advanced machine learning algorithms.

## Data Preprocessing

Converted timestamps to datetime format and sorted chronologically.
Handled outliers and used categorical encoding using frequency.
Dropped redundant features. 
Performed time-aware train-test split (no random shuffling).

## Exploratory Data Analysis (EDA)

Line plots to identify temperature trends and seasonality.
Histograms to analyze precipitation distribution.
Correlation heatmap to examine relationships between variables.
long-term climate patterns and variations in different regions are 

## Time-Series Modeling
ARIMA
Captures trend and autocorrelation in temperature. cannot capture seasonality. 
Uses parameters (p, d, q) for autoregression, differencing, and moving average.

SARIMA
Extends ARIMA to include seasonality but assumes a linear relationship
Uses (p, d, q)to model seasonal cycles.

Random Forest Regressor - Handles nonlinear relationships.

XGBoost Regressor - Gradient boosting algorithm.
Improves accuracy by sequentially correcting prediction errors.

## Model Evaluation

Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) are used as metrics of accuracy.
Temperature shows clear seasonal patterns.
Machine learning models outperform pure statistical models when multiple features are included.
Ensemble predictions improve forecasting stability.
