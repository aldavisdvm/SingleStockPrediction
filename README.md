# Single Stock Future Closing Price Prediction

## Project Description
The purpose of this project is to compare three regressor models in predicting the future closing price of a stock. 
A classifier model is also created for comparison.


### Methods Used

* Machine Learning
* Data Visualization
* Predictive Modeling
* Linear Regression (Ordinary Least Squares)
* Random Forest Regressor
* XGBoost Regressor
* Adaboost Classifier


### Technologies

* Jupyter Notebook
* Python
* Pandas and Numpy
* Scikit-Learn
* Seaborn, Matplotlib, and Plotly


### Data was obtained through yfinance


## Project Summary

Stock data was downloaded and explored. A few features were created using the talib library and checked for correlations. 
An OLS model was created using the next day closing price as a target. A Random Forest and XGB model were also done
for comparison. After categorizing the future close price, an Adaboost Classifier model was also run using this 
as its target.
