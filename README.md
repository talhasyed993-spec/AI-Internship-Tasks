                                                    Machine Learning Tasks Portfolio
Overview

This repository contains three machine learning and data analysis tasks completed usingPython, Pandas, Matplotlib, Seaborn, Scikit-Learn, and Jupyter Notebook. The projects focus on data exploration, predictive modeling, and performance evaluation.

                                                Task 1: Iris Dataset Analysis and Visualization
Objective

To load, inspect, analyze, and visualize the Iris dataset in order to understand feature distributions, relationships between variables, and identify patterns among different flower species.

Dataset Used
Iris Dataset (iris.csv)
Features:
Sepal Length
Sepal Width
Petal Length
Petal Width
Species
Models Applied

No machine learning model was used in this task. The focus was on Exploratory Data Analysis (EDA) and data visualization.

Key Results and Findings
The dataset contains 150 flower samples from three species.
Petal measurements provide strong separation between species.
Histograms revealed feature distributions.
Scatter plots showed relationships among features.
Box plots were used to identify potential outliers.
The dataset is clean and suitable for classification tasks.

                                                    Task 2: Stock Price Prediction
Objective

To predict the next day's stock closing price using historical stock market data obtained from Yahoo Finance.

Dataset Used
Historical stock data retrieved using the yfinance library.
Stock selected: Apple Inc. (AAPL)
Features:
Open Price
High Price
Low Price
Volume
Target:
Next Day Closing Price
Models Applied
Linear Regression
Key Results and Findings
Historical stock data was successfully collected from Yahoo Finance.
A Linear Regression model was trained to predict future closing prices.
Open, High, and Low prices were strong indicators of the next closing price.
Model performance was evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
Actual and predicted prices were visualized for comparison.
The model demonstrated the application of machine learning in short-term stock forecasting.

                                                        Task 3: Heart Disease Prediction
Objective

To predict whether a patient is at risk of heart disease using medical and health-related attributes.

Dataset Used
Heart Disease UCI Dataset
Features include:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Maximum Heart Rate
Exercise-Induced Angina
Other clinical measurements
Target:
Presence or absence of heart disease
Models Applied
Logistic Regression
Key Results and Findings
The dataset contained no missing values and required minimal preprocessing.
Exploratory Data Analysis was performed using:
Count Plots
Histograms
Correlation Heatmaps
Logistic Regression was trained for binary classification.
Model performance was evaluated using:
Accuracy Score
Confusion Matrix
ROC Curve
ROC-AUC Score
Feature importance analysis helped identify factors most associated with heart disease risk.
The model demonstrated how machine learning can support medical decision-making and disease risk assessment.
Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
yfinance

                                                                    Conclusion

These projects demonstrate fundamental machine learning workflows, including data preprocessing, exploratory data analysis, regression modeling,
classification modeling, visualization, and performance evaluation. Together, they provide practical experience in applying machine learning techniques
to real-world datasets from biological, financial, and healthcare domains.
