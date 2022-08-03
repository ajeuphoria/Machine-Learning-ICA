# Machine-Learning-ICA

To create a Electricity Demand forecast for France on an hourly basis up to 48 hours ahead.

Dataset given had 5 years of historical data. 

Used Regression and Time-series analysis. 

**Time Series Algorithm used: **
1. Seasonal ARIMA. 

**Regression Algorithms used :** 
1. Linear Regression.
2. K Nearest Neighbors (KNN) Regressor. 
3. Random Forest Regressor. 
4. XGBoost Regressor.
5. AdaBoost Regressor. 
6. Decision Tree Regressor. 

**Accuracy**

ARIMA (1,0,1) (1,0,1,12)      -     98.92%
XGBoost Regressor             -     97.53%
Random Forest Regressor       -     96.62%
K Nearest Neighbors Regressor -     95.06%
Decision Tree Regressor       -     92.90%
AdaBoost Regressor            -     82.90%
Linear Regression             -     72.20%
