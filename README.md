Customer Purchase Prediction: Data Wrangling and Classification for E-Commerce Analytics

## Overview
This project focuses on building a machine learning system to predict whether a customer is likely to make a purchase based on demographic and behavioral features.
The objective is to assist e-commerce businesses in identifying potential buyers and improving targeted marketing strategies.

## Objective
To demonstrate how machine learning techniques can be applied to e-commerce analytics for predicting customer purchase behavior and enabling data-driven decision-making.

## Dataset
The dataset includes attributes such as age, annual income, number of previous purchases, time spent on the website, discounts availed, and loyalty program membership. Data wrangling techniques were applied to clean and preprocess the dataset, including handling missing values, encoding categorical variables, and aligning features for modeling.

## Algorithms 
Multiple classification algorithms were explored to analyze and compare performance, including:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)

Among these, the Random Forest model provided strong performance due to its ability to capture complex patterns and handle feature interactions effectively. The model predicts both a binary outcome (purchase or not) and a probability score indicating the likelihood of purchase.

To validate the model, real-world data was collected through a Google Form, where participants provided their details. The model was then used to predict their purchase behavior. The results provided insights into model behavior, including a tendency to predict “no purchase” in several cases due to feature influence and classification thresholds.

## Key Features
Data cleaning and preprocessing
Feature engineering based on customer behavior
Implementation and comparison of multiple classification algorithms
Model evaluation using accuracy and probability scores
Real-world testing using survey (Google Form) data


##  How to Run
1. Open the notebook in Google Colab
2. Upload dataset
3. Run all cells
