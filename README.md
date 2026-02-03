# eu-emissions-renewables-forecast

EU-27 emissions vs renewable electricity production (2005–2023) + forecasting (2024–2035)

## Project Overview

This project analyzes the relationship between greenhouse gas emissions and renewable electricity production across EU-27 countries from 2005 to 2023, and provides exploratory forecasts up to 2035.

The analysis focuses on multiple emission sources (CO2, CH4, GHG, N2O, NOx, SO2) and investigates how their historical trends relate to the growth of renewable energy production at country level.

## Objectives

- Identify the most polluting EU countries across different greenhouse gases  
- Analyze long-term emission trends at both country and EU-wide level  
- Study the relationship between renewable electricity production and emissions  
- Explore future scenarios using simple and interpretable forecasting models  

## Methodology

- Data filtering limited to EU-27 countries  
- Feature engineering based on total and average emissions per country  
- Correlation analysis between renewable electricity production and emissions  
- Time-series forecasting using:
  - Linear Regression (baseline)
  - Polynomial Regression (degree 2)
  - Random Forest Regressor (exploratory benchmark)

Model performance is evaluated using MAE, RMSE and R² metrics.  
Model complexity is intentionally kept moderate to emphasize interpretability and robustness.

## Key Findings

- Larger and more industrialized countries (e.g. Germany, France, Italy) are consistently among the highest emitters  
- EU-wide greenhouse gas emissions show a general declining trend after 2005  
- Renewable electricity production is negatively correlated with emissions, although the relationship is moderate  
- Linear regression provides the most stable and interpretable long-term forecasts  
- More complex models (Random Forest, polynomial regression) show strong in-sample performance but limited reliability for long-term extrapolation  

## Notes

This project is intended as an exploratory data analysis and learning exercise.  
Forecasts should be interpreted as indicative trends rather than precise predictions.
