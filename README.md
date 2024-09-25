## Overview

The Diabetes Prediction Web App is designed to provide a quick and easy way to predict whether an individual is diabetic based on a set of inputs 
like glucose levels,blood pressure, skin thickness, insulin levels, BMI, and more.
The prediction is made using a machine learning model trained on a diabetes dataset.

## Technologies Used

- **Python**: The core programming language.
- **Streamlit**: For building the web app.
- **scikit-learn**: For the machine learning model.
- **NumPy**: For numerical computations.
- **Pickle**: For loading the pre-trained machine learning model.

## Model

The app uses a pre-trained machine learning model, which was trained on a diabetes dataset. 
The model has been serialized and saved using **Pickle**.
The user inputs medical information, and the model predicts whether the individual is diabetic.
