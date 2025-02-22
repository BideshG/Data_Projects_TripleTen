# Rusty Bargain Car Sales

## Overview

* Rusty Bargain used car sales service is developing an app to attract new customers. The purpose of this project is to develop a machine learning algorithm that can predict prices of the vehicles.

### Install

This project requires **Python** and the following Python libraries installed:

- [Pandas](http://pandas.pydata.org/)
- [NumPy](http://www.numpy.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
- [lightgbm] (https://lightgbm.readthedocs.io/en/stable/)

### Functionality

* Completes data preprocessing, exploratory data analysis, and statistical data analysis.
* Machine Learning models were created using LinearRegression, DecisionTreeRegressor, RandomForestRegressor, and LightGBM.
* Runtimes for all algorithms were checked along with performance of the models using RMSE.
* The best model was the RandomForestRegressor with a RMSE score of 1611.23. Lightgbm was the second best model but it also had a runtime of less than 1/3 of the time of RandomForestRegressor.
* RandomForestRegressor should be used to determine the price of a vehicle. If a large dataset is being used, LightGBM should be used to reduce runtime.

![rusty bargain](https://github.com/Bidesh-Ghosh/Data_Projects_TripleTen/assets/152648624/16d683d9-df25-4a4e-94e9-7311308dd186)

Datasets available on request.
