# Gold Price Prediction Using RandomForestRegressor

This project is about predicting the price of gold using various features like silver price, amount of gold in stock, etc., with the help of RandomForestRegressor from Scikit-Learn.

## Table of Contents

1. [Dependencies](#dependencies)
2. [Data Collection and Preprocessing](#data-collection-and-preprocessing)
3. [Correlation](#correlation)
4. [Data Splitting](#data-splitting)
5. [Model Training](#model-training)
6. [Model Evaluation](#model-evaluation)
7. [Visualization](#visualization)

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- sklearn

## Data Collection and Preprocessing

The dataset used in this project is named 'gld_price_data.csv'. The initial steps involve loading the dataset, displaying the first and last few rows, checking for null values, and obtaining basic statistics about the dataset.

## Correlation

The correlation between features is assessed, and a heatmap is plotted to visualize this correlation.

## Data Splitting

The features and target variable (gold price) are separated and then split into training and test sets.

## Model Training

A RandomForestRegressor model from Scikit-learn is trained on the training dataset.

## Model Evaluation

The model's performance is evaluated using the R-squared error on the test dataset.

## Visualization

A visualization is constructed to compare actual gold prices with the predicted values from the model.

---

**Note**: To replicate or run the code provided in this project, ensure that you have all the dependencies installed and the dataset 'gld_price_data.csv' placed in the correct directory. 
