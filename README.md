

[//]: # (I must include tools section and add tools images, check proper README design tutorial)
[//]: # (images and style from https://simpleicons.org/)
![Python](https://img.shields.io/badge/Python-3.8-blueviolet?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/pandas-1.4.3-150458?style=for-the-badge&logo=pandas)
![scikit-learn](https://img.shields.io/badge/scikitlearn-0.24.1-F7931E?style=for-the-badge&logo=scikitlearn)
![SciPy](https://img.shields.io/badge/scikitlearn-0.12.2-8CAAE6?style=for-the-badge&logo=scipy)
![keras](https://img.shields.io/badge/Keras-2.9.0-43B02A?style=for-the-badge&logo=keras)
![mySQL](https://img.shields.io/badge/mysql-2B2B2B?style=for-the-badge&logo=mysql)
![Jupyter](https://img.shields.io/badge/jupyter-2B2B2B?style=for-the-badge&logo=jupyter)

# Product Supermarket Sales Prediction

# Abstract
A stage of a business life cycle that requires strategic and careful measures to be put in place is the growth stage. Growth stage comes after the Business has been launched, and part of a business growth can be expansion into more locations.

It however requires proper and critical analysis to know what location and product type is best for a specific location. For example, a tin of milk which sells for N100 in one supermarket branch may also be sold at N110 at another supermarket within the same chain of supermarkets. Hence, there's a need to understand what type of product, market clusters and supermarket type (location, age, size) will give more margin as business is expanded to more locations.

In this analysis, a predictive model is developed using machine learning algorithms to improve and accurately forecasts product sales. The proposed model is especially targeted to identify key characteristics of products and supermarkets driving sales so as to be better informed on an optimal template for expansion of Chuwkwudi Supermarket to other states in Nigeria. The model is not intended to change current subjective forecasting methods. A model based on real supermarket store's data is developed in order to validate the use of the various machine learning algorithms

# Introduction
This is an in house kaggle competition organized by AI+ OAU where the task is to predict product supermarket sales to help identify key characteristics of products and supermarkets driving sales so as to be better informed on an optimal template for expansion of Chukwudi Supermarket to other states in Nigeria.

For this particular problem, I have analyzed the data as a supervised learning problem. In order to forecasts the sales, I have compared different regression models like Linear Regression, Decision Tree, ExtraTreeRegressor, Gradient Boosting, Random Forest, XgBoost and Neural Network.

The data comes in the shape of multiple files BUT to demonstrate my SQL proficiency had to load the data into a MySQL database. First, the train table essentially contains the sales by supermarket, product and so on. The test table contains the same features without the product supermarket sales information, which I am tasked to predict.

# Data Sources
The data has can be seen [here](https://www.kaggle.com/competitions/dsn-ai-oau-july-challenge/data) comes in the shape of multiple files BUT to demonstrate my SQL proficiency had to load the data into a MySQL database. 
The file containing the mysql scripts that created the database and the data is saved as `chukwudi_supermarket.sql` in the `db and data scripts` folder.
The database contain the following tables:
- `train` contains the sales by supermarket, product and so on.
- `test` contains the same features as train but without the product supermarket sales information
- `sample_submission` contains Supermarket id and dummy product supermarket sales values. This serve as a submission template

# Installation
Install all requirements by running the following command
```
pip install requirements.txt
```

# Issues
Incase you have any difficulties or issues while trying to run the app you can raise it on the issues section.

# Pull Requests
If you have something to add or new idea to implement, you are welcome to create a pull requests.

# Give it a Star
If you find this repo useful , give it a star so as many people can get to know it.

# Credits
* AI+ OAU
* [Kaggle-Data source](https://www.kaggle.com/competitions/dsn-ai-oau-july-challenge/data)