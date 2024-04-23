Predicting Price of Pre-Owned Cars

This Python program utilizes Pandas, Seaborn, Scikit-learn libraries to perform exploratory data analysis and build regression models to predict the price of pre-owned cars. The data is loaded from a CSV file (cars_sampled.csv).

Key functionalities of the script:

    Data Loading and Cleaning:
        1.Reads the CSV file using Pandas.
        2.Creates a copy of the data for manipulation.
        3.Analyzes the data structure and provides summary statistics.
        4.Drops irrelevant columns and removes duplicate records.
        5.Handles missing values by identifying and addressing them through techniques like dropping rows or imputation (filling missing entries).
        6.Performs data cleaning steps including identifying outliers and handling them appropriately.

    Exploratory Data Analysis (EDA):
        1.Analyzes various features of the dataset using visualization techniques with Seaborn.
        2.Identifies correlations between features (price, mileage, etc.) and target variable (price).
        3.Identifies and explores categorical features using visualizations and statistical methods.

    Feature Engineering:
        1.Creates new features based on existing ones (e.g., combining year and month of registration into age).
        2.Encodes categorical variables into dummy variables for modeling purposes.

    Model Building:
        1.Splits the data into training and testing sets.
        2.Builds two sets of models - one where missing values are omitted and another where they are imputed using median values.
        3.Implements two machine learning algorithms - Linear Regression and Random Forest Regression.
        4.Trains the models on the training data.
        5.Evaluates the performance of the models on the testing data using R-squared and Root Mean Squared Error (RMSE) metrics.
        6.Compares the performance of models built with and without missing value imputation.

Outputs:

    The program generates various visualizations throughout the script using Seaborn to understand the data distribution and feature relationships.
    Performance metrics (R-squared and RMSE) are printed for all the models built.
    A final section summarizes the key findings and compares the performance of the different models.

Note:

    This script assumes the required libraries (Pandas, Seaborn, Scikit-learn) are installed.
    The CSV file containing the car data (cars_sampled.csv) needs to be placed in the same directory as the script.
