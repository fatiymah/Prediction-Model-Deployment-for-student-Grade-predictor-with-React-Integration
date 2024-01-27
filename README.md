# Prediction-Model-Deployment-for-student-Grade-predictor-with-React-Integration
Overview:  Deployed scikit-learn model with Flask API. Evaluated using metrics like R2, MAE, MSE, Accuracy, etc. README guides replication and React integration for user-friendly interactions.


**Machine Learning Model Deployment with React Integration**

## Overview

This repository demonstrates the deployment of a machine learning model for predictive analysis, employing regression and classification techniques. The project includes Python code for data preprocessing, model training using scikit-learn, and a Flask API for deployment. Additionally, it provides guidance on integrating the predictive model into a React front-end, enabling user-friendly interactions.

## Getting Started

Follow these steps to reproduce the results and deploy the model:

1. **Data Processing:** Utilize the provided Python sklearn lib for cleaning and transforming the dataset.

2. **Model Training:** The Jupyter Notebook (`model_training.ipynb`) illustrates the application of Linear Regression and Random Forest algorithms. The best model is saved for deployment.

3. **Flask API Deployment:** The py file contains a Flask API to deploy the trained model. Run `app` to start the server.

4. **React Integration:** Refer to the `react_integration` directory for the React front-end code. Follow the README in that directory for setup instructions.

## Model Evaluation

Metrics such as R2 Score, MAE, MSE, RMSE (for regression), and Accuracy, Confusion Matrix, Precision, Recall, F1 Score (for classification) are provided in the evaluation section of the Jupyter Notebook.

## Dependencies

- Python 3.x
- scikit-learn
- Flask
- React (for front-end integration)

## Folder Structure

- `model_training.ipynb`: Jupyter Notebook for model training and evaluation.
- Flask API for model deployment.
- `react_integration`: React front-end integration code.

For detailed instructions on deploying the model and integrating it with React, refer to the respective sections above. Feel free to reach out for any questions or improvements. Happy coding!
