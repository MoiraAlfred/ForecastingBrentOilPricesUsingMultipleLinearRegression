# Forecasting Brent Oil Prices Using Multiple Linear Regression

## Project Overview  
This project focuses on building a predictive model to estimate Brent crude oil prices using Multiple Linear Regression. The model leverages short-term moving averages to capture trends and forecast future prices with high consistency and interpretability.

## Objectives

- Apply Multiple Linear Regression to time-series financial data
- Engineer meaningful features using moving averages
- Visualize historical price behavior and model predictions
- Evaluate model performance using standard regression metrics

## Methodology

- **Data Preparation**: Cleaned and preprocessed historical Brent oil price data. Converted date fields and removed incomplete records.
- **Feature Engineering**: Created 3-day and 9-day moving average columns to reflect short-term price trends.
- **Model Development**: Trained a linear regression model using the engineered features as inputs. Ensured reproducibility with a fixed random seed.
- **Evaluation and Interpretation**: Visualized prediction accuracy through scatterplots and assessed the model using regression performance indicators.

## Tools and Technologies

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## Key Insights

- Moving averages serve as effective predictors for oil prices within short time frames
- The model provides clear, interpretable results suitable for financial forecasting
- Visual evaluation confirms close alignment between predicted and actual values

## Conclusion

This project demonstrates the application of regression modeling to a real-world economic problem. It highlights the effectiveness of simple, well-constructed models in providing reliable forecasts for commodity pricing.


