# Student Performance Prediction Web Application

## Overview

This project aims to predict student performance based on various factors such as gender, ethnicity, parental level of education, lunch, and test preparation course. The prediction model is integrated into a web application using Flask, allowing users to input data and receive predictions on student performance.

## Project Structure

The project is structured as follows:

- `src/`: Contains the source code for the web application.
  - `pipeline/`: Contains the prediction pipeline code.
  - `utils/`: Contains utility functions used in the project.
- `templates/`: Contains HTML templates for the web pages.
- `static/`: Contains static files (e.g., CSS, JavaScript) for the web application.
- `artifacts/`: Contains trained model and preprocessor objects.
- `app.py`: Main Flask application file.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project README file.

## Setup

1. Clone the repository:


2. Install dependencies:


3. Run the Flask application:


4. Access the web application in your browser at `http://localhost:5000`.

## Usage

1. Navigate to the home page of the web application.
2. Enter the required information, such as gender, ethnicity, parental level of education, lunch, test preparation course, reading score, and writing score.
3. Click on the "Predict" button to submit the form and receive the predicted student performance.

## Model Training

The prediction model was trained using a dataset obtained from [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977). Various machine learning algorithms were evaluated, including Linear Regression, Lasso, Ridge, K-Neighbors Regressor, Decision Tree, Random Forest Regressor, XGBRegressor, CatBoosting Regressor, and AdaBoost Regressor. The model with the highest performance metrics was selected for integration into the web application.

