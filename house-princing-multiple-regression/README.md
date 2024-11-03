# house-princing-multiple-regression

## House Pricing Prediction with Multiple Linear Regression

This project utilizes multiple linear regression techniques to predict house prices based on various features. The dataset includes information such as area, number of garages, bathrooms, fireplaces, presence of marble finishing, and number of floors.

## Model Evaluation Metrics:

* **Coefficient of Determination (R²)**: 0.67
* **Mean Squared Error (MSE)**: 5.02e+07
* **Root Mean Squared Error (RMSE)**: 7.08e+03

## Dataset Description
The dataset contains information about house prices and their associated features. The variables include:

* `prices`: House prices in a specific currency unit.
* `area`: House area in square meters.
* `garage`: Number of garage spaces.
* `bathrooms`: Number of bathrooms.
* `fireplace`: Number of fireplaces in the house.
* `marble`: Binary indicator (0 or 1) if the house has white marble finishing.
* `floors`: Binary indicator (0 or 1) if the house has more than one floor.

## Project Stages
* **Understanding the Dataset**: Importing the necessary libraries and reading the dataset.
* **Preliminary Analysis**: Initial exploration of the data, including descriptive statistics and a correlation matrix to understand relationships between variables.
* **Data Visualization**: Using boxplot and histogram graphs to understand the data distribution and identify possible outliers. Also, scatter plots to observe relationships between variables.
* **Estimating a Linear Regression Model**: Splitting the data into training and test sets. Instantiating the linear regression model and fitting it to the training data.
* **Point Forecasts**: Generating predictions for test data and specific examples using the trained model.
* **Model Evaluation**: Assessing the model's performance using metrics such as the coefficient of determination (R²), mean squared error (MSE), and root mean squared error (RMSE).