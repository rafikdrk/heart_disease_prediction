# Heart Disease Prediction using Machine Learning Classification Models

## Project Overview

This project focuses on the prediction of heart disease using classification models based on various patient attributes. The dataset includes key features such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, maximum heart rate, exercise-induced angina, old peak, and ST slope. The target variable is the presence or absence of heart disease.

## Objectives of the Project

The primary objectives of this project are as follows:

1. Data Exploration and Preparation:
   - Explore the dataset to understand its structure, features, and data distribution.
   - Handle missing values, outliers, and duplicates as part of data preparation.

2. Model Training:
   - Build and evaluate machine learning classification models to predict the presence of heart disease based on patient attributes.

3. Model Deployment:
   - Deploy the trained model as a web service, allowing users to input patient data and receive predictions.

## Project Components

The project is organized into the following components:

1. Data Exploration and Preparation:
   - Data exploration and data preparation steps can be found in the data_preparation.ipynb Jupyter Notebook.

2. Model Training:
   - Trained classification models are stored in the models/ directory.

3. Model Deployment as a Web Service:
   - The model is deployed as a web service using Flask. The web service code can be found in the web_service.py script.

4. Docker Deployment:
   - To make model deployment easy and consistent, Docker is utilized for local deployment. You can build and run the Docker image using the provided Dockerfile.

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine.

2. Set up a virtual environment (e.g., using virtualenv or conda) and install the required dependencies:

  
bash
   pip install -r requi
rements.txt
   

3. Explore the project com
ponents and execute the necessary scripts to explore, train, and deploy the model.

## Expected Outcomes

By the end of this project, the goals are:

1. Develop a robust machine learning classification model for heart disease prediction.
2. Provide a web service for users to interact with the model and receive predictions.
3. Contribute valuable insights into the field of medical data analysis and predictive modeling.
4. Improve the ability to predict the presence of heart disease based on patient attributes, potentially assisting medical professionals in early diagnosis and treatment.

This project demonstrates the application of machine learning in the healthcare domain and its potential to enhance the accuracy of medical diagnoses.

Feel free to customize and expand this README to include specific details about your project, data sources, findings, and any other relevant information.