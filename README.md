# Classification-Model-Birth-Weight-Prediction

## Introduction
During pregnancy, ensuring the health of the baby is critical. Low birthweight is a significant concern as it can indicate potential complications and health risks for newborns. In this project, I have taken on the role of a public health consultant tasked with analyzing and predicting birthweight. Using various machine learning techniques, I aim to identify key factors influencing birthweight. The goal is to develop a predictive model that can help healthcare providers and public health officials identify at-risk pregnancies and implement preventative measures to improve neonatal outcomes. This project involves exploring the data, engineering relevant features, building and evaluating machine learning models, and providing actionable insights based on the analysis.

## Overview
Implemented different models including KNN, Random Forest, Decision Tree, Logistic Regression, Ridge Classification, and GBM. KNN showed high precision (1.0) but very low recall (0.05). The Random Forest Classifier emerged as the best model with a precision of 0.4444 and a recall of 0.2. Higher recall is crucial for identifying most low birthweight cases, ensuring that at-risk cases are detected for timely intervention and reduced health risks.

**Target Variable**: The model predicts whether a newborn is of low birthweight (binary classification: 0 for normal birthweight, 1 for low birthweight).

**Kaggle Dataset Performance**: Using the trained model on a Kaggle dataset for prediction resulted in an accuracy of 70%.

## Case - Public Health Analysis

**Audience**: Public health officials and healthcare providers.

**Goal**:To predict low birthweight in newborns and provide insights into the factors influencing birthweight, aiding in the development of preventative measures and interventions.

**Target Users**: Pregnant women, healthcare providers, and public health officials.

**Data**:Historical Maternal health records ,birthweight, and prenatal care details.

## Analysis Outline
Part 1: Exploratory Data Analysis
Part 2: Feature Engineering
Part 3: Model Building
Part 4: Model Evaluation
Part 5: Insights and Recommendations

## Conclusion
The Random Forest Classifier is the best model for predicting low birthweight, with a balanced accuracy of 70%. This model helps identify potential risks and provides insights into preventative measures, supporting public health efforts to ensure healthier pregnancies and newborns.
