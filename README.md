# Forest Fire Prediction using Machine Learning (Regression)

This project focuses on predicting **forest fire severity** using **Machine Learning regression techniques**.  
The goal is to analyze environmental and meteorological factors and estimate the likelihood or intensity of forest fires, helping in early warning and preventive planning.

---

## Project Description

Forest fires are influenced by multiple climatic and environmental conditions such as moisture levels, rainfall, and fuel conditions.  
In this project, a **regression-based machine learning model** is trained on historical forest fire data to predict fire behavior.

The trained model is then integrated into a **Flask web application**, allowing users to input real-world parameters and obtain predictions through a simple web interface.

---

## Dataset Information

The project uses the **Algerian Forest Fires Dataset**, which contains weather and fire-related attributes collected from two regions.

### Key Features Used:
- **Rain** – Rainfall amount
- **FFMC** – Fine Fuel Moisture Code
- **DMC** – Duff Moisture Code
- **ISI** – Initial Spread Index
- **Classes** – Fire occurrence indicator
- **Region** – Region identifier

**Target:**  
Predict forest fire severity using regression models.

---

## Machine Learning Approach

- Exploratory Data Analysis (EDA)
- Feature Engineering and Scaling
- Regression Model Training
- Model Evaluation and Selection
- Final model serialization using Pickle

### Models Explored:
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- ElasticNet Regression  

✔ **Ridge Regression** was selected for deployment due to better generalization performance.

---

## Web Application Overview

A **Flask-based web application** is built to deploy the trained regression model.

### Application Features:
- User-friendly HTML interface
- Accepts fire-related input parameters
- Applies preprocessing using saved scaler
- Predicts forest fire severity in real time

---

## Outcome

- Successfully built a regression-based forest fire prediction model  
- Deployed the trained model using Flask  
- Created an end-to-end ML pipeline from data analysis to deployment  

This project demonstrates practical implementation of **machine learning regression**, **model deployment**, and **end-to-end ML workflow**.


