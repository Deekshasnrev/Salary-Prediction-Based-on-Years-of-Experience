# Salary-Prediction-Based-on-Years-of-Experience
This project involves analyzing and predicting salaries based on the years of experience using a dataset named Salary_Data.csv. The project includes exploratory data analysis (EDA), data visualization, and building a linear regression model to predict salaries.

# Table of Contents
1. Introduction
2. Project Structure
3. Data Description
4. Exploratory Data Analysis
5. Data Visualization
6. Linear Regression Model
7. Evaluation Metrics
8. Requirements
9. Conclusion

# Introduction
The goal of this project is to understand the relationship between years of experience and salary and to build a predictive model using linear regression. By analyzing and visualizing the data, we aim to gain insights that can help in predicting salaries based on the number of years of experience.

# Project Structure
The project consists of the following key steps:
Data Loading and Initial Exploration
Data Visualization
Building a Linear Regression Model
Model Evaluation

# Data Description
The dataset Salary_Data.csv contains two main features:
YearsExperience: The number of years of experience of an individual.
Salary: The salary of the individual.

# Exploratory Data Analysis
Initial exploration of the dataset includes:
Displaying the first few rows of the dataset.
Checking the shape of the DataFrame.
Generating a concise summary of the DataFrame.
Descriptive statistics of numerical features.
Identifying missing values.

# Data Visualization
To understand the relationships between different variables, the following visualizations are created:
Scatter Plot: Relationship between YearsExperience and Salary.
Heatmap: Correlation between YearsExperience and Salary.

# Linear Regression Model
The following steps are taken to build the linear regression model:
Setting up the feature x (YearsExperience) and target y (Salary).
Splitting the data into training and test sets with a test size of 30%.
Training a LinearRegression model using the training data.
Making predictions on both training and test data.
Plotting the predicted vs actual values for training data.

# Evaluation Metrics
The performance of the linear regression model is evaluated using the following metrics:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
R-squared (R2) Score

# Requirements
The project requires the following Python libraries:
numpy
pandas
matplotlib
seaborn
scikit-learn

# Conclusion
This project provides insights into the relationship between years of experience and salary and demonstrates the use of linear regression for predictive analysis. The model's performance metrics indicate its effectiveness in predicting salaries based on years of experience. Future improvements could include exploring additional features and advanced modeling techniques to enhance prediction accuracy.
