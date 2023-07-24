# Heart Disease Prediction: A Machine Learning Approach

This repository contains a Jupyter notebook which leverages Python-based machine learning and data science libraries in an attempt to construct a machine learning model capable of predicting the likelihood of heart disease in a patient given their medical attributes.

The project follows the given steps:

1. Problem Definition
2. Data Acquisition
3. Evaluation Metric Definition
4. Features Selection
5. Model Building
6. Experimentation

## Problem Definition

The goal of this project is straightforward: can we build a model that, given certain clinical parameters, is capable of accurately predicting whether or not a patient has heart disease?

## Data

The data utilized in this project comes from the UCI Machine Learning Repository (https://archive.ics.uci.edu/) who maintain several hundred datasets as a service to the machine learning community.

## Evaluation

The preliminary aim for this project was to construct a proof of concept model with an accuracy of 90% or more in predicting whether a patient has heart disease. If this level of accuracy is attainable, further development and fine-tuning of the model will be pursued.

## Features

The dataset contains the following features:

- **age**: The patient's age in years
- **gender**: The gender of the patient. Typically encoded as 0 and 1, where one value represents male and the other female.
- **cp**: Chest pain type. It's a value from 0-3 representing different types of angina (chest pain) the patient has experienced.
- **trestbps**: Resting blood pressure. It represents the patient's blood pressure (in mm Hg) while at rest.
- **chol**: Serum cholesterol. This is a measure of the patient's cholesterol level, measured in mg/dl.
- **fbs**: Fasting blood sugar. This feature is typically encoded as 0 or 1, representing whether the patient's fasting blood sugar was higher than 120 mg/dl (1 = true; 0 = false).
- **restecg**: Resting electrocardiographic results. It's a value from 0-2 representing different states of the patient's heart functionality based on an ECG while at rest.
- **thalach**: Maximum heart rate achieved. It indicates the maximum heart rate of the patient recorded during a thallium stress test.
- **exang**: Exercise induced angina. This feature is typically encoded as 0 or 1, representing whether the patient experienced angina (chest pain) during exercise (1 = yes; 0 = no).
- **oldpeak**: ST depression induced by exercise relative to rest. It indicates the difference in parts of the patient's ECG signal between when the patient is at rest and during/after exercise.
- **slope**: The slope of the peak exercise ST segment. It's a value from 0-2 representing the slope of the line segment in the patient's ECG between certain heartbeats during the peak of exercise.
- **ca**: Number of major vessels (0-3) colored by fluoroscopy. It indicates the number of the patient's major blood vessels visible in a fluoroscopic image.
- **thal**: A short form for thalium heart scan. This is a measure of blood flow to the heart, with 3 indicating normal blood flow and 6-7 indicating a fixed or reversible defect.
- **heart_diagnosis**: This is the target variable. It is typically encoded as 0 or 1, representing whether or not the patient has heart disease.

## Model Building

Upon cleaning and preparing the data for modeling, we've experimented with three different types of machine learning models to assess their effectiveness in this specific prediction task.

## Experimentation

If the model doesn't meet the defined evaluation metric, we'll need to reassess our approach. This could entail gathering more data, enhancing the model by tuning its hyperparameters, or employing a different model altogether.