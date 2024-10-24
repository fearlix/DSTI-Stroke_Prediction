# Stroke Risk Prediction
## Abstract
According to the World Health Organisation (WHO), stroke is the 2 nd leading cause of death globally, responsible for approximately 11% of total deaths.
The dataset provided is used to predict whether a patient is likely to get a stroke based on input parameters like gender, age, various diseases and smoking status.

## Project Overview
This project implements multiple machine learning models (Logistic Regression, Random Forest, Support Vector Machine, and Decision Tree)
to evaluate stroke risk using patient data. The aim is to identify key factors influencing stroke occurrence and develop predictive models.
It was done while doing my studies at DSTI as a SPOC.

## Problem Statement
What characteristics in a patient’s profile increase or decrease their risk of having a stroke? 
How can we identify these factors and reduce healthcare expenses for patients? 
What is the main reason for stroke?

## Data source
The data set has the following columns:
1) id: unique patient identifier
2) gender: “Male”, “Female” or “Other”
3) age: age of the patient
4) hypertension: 0 (if the patient doesn’t have hypertension) or 1 (if the patient has hypertension)
5) heart_disease: 0 (if the patient doesn’t have a heart disease) or 1 (if the patient has a heart disease)
6) ever_married: “No” or “Yes”
7) work_type: “children”, “Govt_job”, “Never_worked”, “Private” or “Self-employed”
8) Residence_type: “Rural” or “Urban”
9) avg_glucose_level: average glucose level in the blood
10) bmi: body mass index
11) smoking_status: “formerly smoked”, “never smoked”, “smokes” or “Unknown” (in this case the information for the patient is not available)
12) stroke: 1 (if the patient had a stroke) or 0 (if the patient didn’t have a stroke)

## Goal
Data Analysis: Perform data processing and cleaning, followed by exploratory data analysis (EDA) to visualize relevant attributes and identify patterns related to stroke risk.
Feature Selection: Utilize feature engineering and pruning techniques to select meaningful features, justifying their inclusion based on their impact on model performance.
Model Training: Choose and train multiple machine learning models, comparing their effectiveness and explaining the rationale behind model selection.
Model Evaluation: Define evaluation metrics (e.g., accuracy, precision, recall) to assess model performance and interpret the results for stroke prediction effectiveness.
Project Report: Create a brief report summarizing the methodology, findings, and insights from the project.
