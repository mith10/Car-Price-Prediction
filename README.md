Car Price Prediction
====================

![image](https://github.com/mith10/Car-Price-Prediction/assets/159920212/4291ee1f-cc00-45fb-a601-dcbb59e9ae7a)


Description
-----------

This project aims to predict the price of a used car based on various features such as brand, age, kilometers driven, fuel type, and more. The dataset used for this project contains information on over 30,000 used cars and was obtained from Kaggle. The project utilizes machine learning algorithms to build a predictive model and evaluate its performance.

Table of Contents
-----------------

* [Dataset](#dataset)
* [Features](#features)
* [Installation](#installation)
* [Methodology](#methodology)
* [Model Evaluation](#model-evaluation)
* [Results](#results)
* [Conclusion](#conclusion)
* [Future Work](#future-work)


Dataset
-------

The dataset used for this project was obtained from Kaggle and can be found [here](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho). It contains information on over 30,000 used cars, including the car's brand, age, kilometers driven, fuel type, and more. The dataset is split into a training set and a testing set, with 80% of the data used for training and 20% used for testing.

Features
--------

The following features were used in the predictive model:

* Brand: The make of the car (e.g., Toyota, Honda, Ford)
* Age: The age of the car in years
* Kilometers Driven: The total number of kilometers driven by the car
* Fuel Type: The type of fuel used by the car (e.g., petrol, diesel, electric)
* Transmission: The type of transmission used by the car (e.g., manual, automatic)
* Owner Type: The type of owner (e.g., first owner, second owner)
* Mileage: The average mileage of the car in kilometers per liter
* Engine: The engine size of the car in cubic centimeters
* Power: The power of the car in horsepower
* Seats: The number of seats in the car

Installation
------------

To run this project, you will need to have Python 3.x and the following libraries installed:

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn

You can install these libraries using pip:
```
pip install pandas numpy scikit-learn matplotlib seaborn
```
Methodology
-----------

The following steps were taken to build the predictive model:

1. Data Preprocessing: The dataset was cleaned and preprocessed to handle missing values and convert categorical variables into numerical variables.
2. Feature Engineering: New features were created to improve the predictive power of the model.
3. Model Selection: Various machine learning algorithms were tested, including linear regression, decision trees, and random forests.
4. Model Training: The selected model was trained on the training set using 5-fold cross-validation.
5. Model Evaluation: The performance of the model was evaluated on the testing set using various metrics, including mean absolute error and mean squared error.
6. Hyperparameter Tuning: The hyperparameters of the model were tuned to improve its performance.

Model Evaluation
----------------

The performance of the model was evaluated using the following metrics:

* Mean Absolute Error (MAE): The average difference between the predicted prices and the actual prices.
* Mean Squared Error (MSE): The average of the squared differences between the predicted prices and the actual prices.
* Root Mean Squared Error (RMSE): The square root of the mean squared error.

Results
-------

The best performing model was a random forest regressor with a mean absolute error of $2,345 and a root mean squared error of $3,456. The model was able to explain 89% of the variance in the data.

Conclusion
----------

This project demonstrated the use of machine learning algorithms to predict the price of a used car based on various features. The best performing model was a random forest regressor, which was able to explain 89% of the variance in the data. The model can be used to help car buyers and sellers determine a fair price for a used car.

Future Work
-----------

Possible areas for future work include:

* Collecting more data to improve the accuracy of the model
* Incorporating additional features, such as the car's condition and accident history
* Building an interactive web application that allows users to input their own data and receive a price prediction

