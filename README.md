# Stock-Direction-Prediction
Key Features: <br>
Stock market variables: Parent Indices Data (NIFTY 50, NIFTY COMMODITIES, NIFTY INFRASTRUCTURE). <br>
Exogenous variables: USD INR Exchange Rate, Interest Rate (Repo Rate), Crude Oil Prices, FPI Data. <br>
Feature Engineering to create extra variables such as EMA, RSI, Log Returns, Price Change, Volume Ratio, Volatility. <br>
Multicollinearity Check: Correlation Matrix & Variance Inflation Factor (VIF). <br>
Time Series Cross-Validation (TSCV: 5 Fold) & time series train-test split (80:20). <br>
Models: Logistic Regression, Support Vector Classification (SVC), Random Forest Classifier, Adaboost Classifier, Gradient Boost Classifier, XGBoost Classifier, LightGBM Classifier. <br>
Price going up labelled as 1 and going down as 0. <br>
Printed classification report, ROC AUC Score and plotted ROC Curve. <br>
As features had multicollinearity, so linear regression and SVC performed better than expected. Disregarding those, XGBoost performed the best (ROC AUC Score: 0.76).
