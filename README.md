# varun_final-project

Forecasting COVID-19 Trends Using Historical Data

Overview: The use of machine learning algorithms to predict the number of COVID-19 cases in the US is examined in this research. Using historical data of confirmed cases, deaths, and recoveries, the goal is to evaluate the predictive performance of several models, such as XGBoost, Random Forest, and Linear Regression.

Features:
Pre-processing: Filtering and Sorting, Feature Engineering and Missing Value Handling by aggregating asset-related columns.
Exploratory Data Analysis(EDA):

7-day rolling averages.
Visualized monthly trends for Confirmed Cases, Deaths, and Recovered to observe long-term patterns.
Created a heatmap to display relationships between numeric features. This helps identify highly correlated variables and understand the data's structure.
Machine learning models:

XG Boost
Random forest regressor
Linear Regression
Evaluation metrics:

Mean squared error (MSE)
R- squred
MAE
Dataset:

Date
Country/Region
Confirmed
Deaths
Recovered
Active Cases
Latitude and Longitude
Preprocessing Steps:

Selected features for modeling: New Cases, New Deaths, and Confirmed_7day_Avg.
Target variable: Confirmed.
Split the dataset into training and testing sets using an 80-20 ratio for model evaluation.
Trained models: XGBoost Regressor, Random Forest Regressor, and Linear Regression.
Evaluated models using metrics like Mean Squared Error (MSE) and R-squared (R²).
Plotted actual vs. predicted values for all models and compared their performance visually.
Prerequisites:

Python 3.x
Required libraries:

pandas
numpy
sk-learn
seaborn
matplotlib
xgboost
