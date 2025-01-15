# Project Overview:
Problem Statement: Predict whether a passenger survived or not on the Titanic based on their characteristics (e.g., age, sex, class).
Dataset: Titanic dataset (available in Excel format). The dataset contains passenger information like class, sex, age, fare, survival status, etc.
Technology Stack:
Data Preprocessing: Pandas, Scikit-learn
Model: Random Forest Classifier (Sklearn)
Web Deployment: Flask or FastAPI for creating a RESTful API
1. Data Collection & Preprocessing:
The first step involves reading the Titanic dataset and performing necessary preprocessing tasks.

Steps for Data Preprocessing:
Handle Missing Values: Fill missing values for columns such as age (with median) and embarked (with mode).
Categorical Encoding: Convert categorical variables like 'sex' into numerical values (0 for female, 1 for male).
Feature Selection: Drop columns like 'name', 'ticket', and 'cabin' as they are not necessary for prediction.
Feature Scaling: Standardize numerical features like age and fare for better model performance.
Train/Test Split: Split the dataset into training and testing sets for evaluation.
