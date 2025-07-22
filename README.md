# Employee-Salary-Predictor, By Bhupesh-L-D
Overview
This project aims to build a machine learning model for predicting employee salaries based on input features such as age, education, occupation, and working hours per week. The classification model will categorize whether an employee earns more than $50k or $50k and below.

Project Structure
Data Preparation

Data is split into training and testing datasets.
Various preprocessing techniques are applied.
Model Selection

# Several classification models are implemented:
> Logistic Regression.

> Random Forest Classifier.

> K-Nearest Neighbors (KNN).

> Gradient Boosting Classifier
## Logistic Regression
   A simple and efficient linear model used for binary and multi-class classification.
## Random Forest Classifier: 
   An ensemble method that builds multiple decision trees and merges their outputs for accurate and robust predictions.

## K-Nearest Neighbors (KNN): 
   A non-parametric method that classifies data points based on the majority class among their nearest neighbors.

## Gradient Boosting Classifier: 
  A powerful boosting algorithm that builds models sequentially to correct the errors of prior models, improving performance
  
> Accuracy, precision, recall, and F1-score metrics are calculated for evaluating model performance.

# User Interface
A user-friendly application is developed using Streamlit to allow end-users to input their details and predict salary classification.
### Dependencies
>Python 3.x
### Libraries:
>scikit-learn.

>pandas.

>streamlit.

>joblib.

>ngrok (for making the app publicly accessible).

### Installation

1.Clone the repository.
2.Navigate to the project directory.
3.Install required packages
------------------------------------------------------
### bash

>pip install -r requirements.txt
------------------------------------------------------
Start the Streamlit app:
------------------------------------------------------
### bash

>streamlit run app.py
------------------------------------------------------
# Usage
1.Input employee details into the provided Streamlit interface.
2.Click on "Predict Salary Class" to get the salary classification.
3.Optionally, upload a CSV file for batch predictions.

# Model Performance
The results of various models are displayed in terms of 
1. Accuracy along with
2. Precision,
3. Recall, and
4. F1-score to help visualize model performance and effectiveness.
   
# Conclusion
This project demonstrates the application of various machine learning models for classification tasks and provides an interactive interface for user engagement, showcasing how data-driven insights can guide salary decisions in an employment context.

# Future Work
Experiment with hyperparameter tuning for better model performance.
Integrate more features to improve prediction accuracy.
Add a feedback loop mechanism to continuously improve the model based on user input.
