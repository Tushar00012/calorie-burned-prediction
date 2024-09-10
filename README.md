# Calorie-burned-prediction

## Overview

This project involves creating a calorie burn prediction model using the XGBRegressor algorithm. The model predicts the number of calories burned based on various physical activity metrics. The project includes data preprocessing, model training, evaluation, and deployment via a Flask web application.

## Project Components

Data Collection and Preprocessing

Model Training and Evaluation

Web Application Deployment

## Technologies Used

Python: Programming language used for data processing and model development.

XGBoost: Machine learning algorithm for building the regression model.

Flask: Web framework for creating a web interface to interact with the model.

HTML/CSS: For the web application's frontend design.

Joblib: To save and load the trained model.

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib & Seaborn: For data visualization.

### Datasets
calories.csv: Contains calories burned.

exercise.csv: Contains user data including gender, age, height, weight, exercise duration, heart rate, body temperature

## File Descriptions
caloriepredict1.py: Contains code for data preprocessing, model training, evaluation, and saving the model.

app.py: Flask application code for serving the model via a web interface.

templates/index.html: HTML file for the web application's frontend.
