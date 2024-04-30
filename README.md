# FDI-data-analysis
## Analysis of Foreign Direct Investment (FDI) in India
This repository is dedicated to analyzing FDI trends in India using advanced time-series statistical methods
## Objectives
Conduct comprehensive analysis across various sectors of the Indian economy.
Forecast future FDI values for individual sectors with accuracy
## Methodology & Execution
Utilized univariate time series datasets sourced from official government platforms, encompassing FDI data across diverse economic sectors.
Employed exploratory data analysis techniques to delve into the top five sectors, both pre- and post-2014 governmental transition.
Notable shift observed in FDI distribution, with the Computer Software & Hardware sector superseding the Construction development sector post-BJP governance.
Transformed non-stationary time series into stationary through differencing techniques.
Augmented Dickey Fuller test employed to confirm stationarity, with focus on p-value and test statistics.
Determined optimal ARIMA model parameters via systematic grid search, prioritizing lowest AIC and BIC values.
Model fitting conducted based on identified optimal parameters.
## Model Evaluation
# Key diagnostic criteria for model assessment include:

Residual plots exhibiting absence of discernible patterns.
Histogram and density estimates closely aligning with N(0,1) distribution.
Q-Q plot showcasing residuals aligning along the red line.
Minimal significant correlations in correlograms beyond lag 0 (95% confidence).
## Forecasting
Model performance evaluated through forecasting exercises, particularly focused on the Services sector.
## Conclusion
The developed model demonstrates proficiency in predicting FDI trends within specific sectors with reasonable confidence. However, enhanced data volumes and thorough hyper-parameter tuning are imperative for improved accuracy.
Future endeavors aim to expand data accessibility, potentially incorporating monthly or even weekly data for comprehensive analysis across sectors.
Limitations include the inability to showcase country-specific FDI dependencies due to data constraints. Additionally, factors such as GDP fluctuations and economic growth potential remain unexplored.
Addressing seasonal trends through advanced models like SARIMA is essential for optimizing resource allocation and fiscal planning.
Exploration of advanced techniques such as LSTM using Deep Learning warrants sufficient data availability, marking a potential avenue for future research.
