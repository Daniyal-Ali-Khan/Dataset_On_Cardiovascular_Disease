# Cardiovascular Disease Dataset Analysis and Prediction

## Overview

This repository contains the analysis and prediction of cardiovascular disease using a dataset that includes various health-related features. The analysis involves Exploratory Data Analysis (EDA) to understand the dataset's characteristics and a machine learning model to predict the likelihood of cardiovascular disease.

## Dataset

The dataset, named "Cardiovascular_Disease_Dataset.csv," includes the following features:

- **patientid:** Unique identifier for each patient
- **age:** Age of the patient
- **gender:** Gender of the patient (1 for male, 0 for female)
- **chestpain:** Type of chest pain experienced (0-3)
- **restingBP:** Resting blood pressure
- **serumcholestrol:** Serum cholesterol levels
- **fastingbloodsugar:** Fasting blood sugar (> 120 mg/dl, 1 for true, 0 for false)
- **restingrelectro:** Resting electrocardiographic results (0-2)
- **maxheartrate:** Maximum heart rate achieved
- **exerciseangia:** Exercise-induced angina (1 for yes, 0 for no)
- **oldpeak:** ST depression induced by exercise relative to rest
- **slope:** Slope of the peak exercise ST segment (0-2)
- **noofmajorvessels:** Number of major vessels colored by fluoroscopy (0-3)
- **target:** Presence of cardiovascular disease (1 for yes, 0 for no)

## Exploratory Data Analysis (EDA)

The analysis involves visualizing the distribution of the target variable and exploring the correlation between features. Additionally, histograms of numerical features provide insights into their distributions.

## Machine Learning Model

A Random Forest Classifier is utilized to predict the presence of cardiovascular disease. The data is split into training and testing sets, features are standardized, and the model is trained and evaluated.

## Results

- **Accuracy:** [insert accuracy here]
- **Confusion Matrix:**
  [insert confusion matrix here]
- **Classification Report:**
  [insert classification report here]
