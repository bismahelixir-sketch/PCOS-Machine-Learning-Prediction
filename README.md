# PCOS-Machine-Learning-Prediction
In this project, I built and compared two supervised machine learning models—Naive Bayes and Decision Tree—to predict Polycystic Ovary Syndrome (PCOS) using patient clinical data. The goal was to determine which model better identifies PCOS based on features such as BMI, testosterone level, age, and antral follicle count.
## Overview
This project predicts the likelihood of Polycystic Ovary Syndrome (PCOS) using machine learning techniques in R. The project explores dataset of 1,000 patient records from Kaggle containing BMI, age, testosterone level, antral follicle count, menstrual irregularity, and PCOS diagnosis.
## Objectives
Explore healthcare data
Visualize important variables
Build classification models
Compare model performance
Evaluate prediction accuracy
## Data Cleaning 
Converted categorical variables to factors.
Removed Menstrual_Irregularity because it produced a zero-variance issue.
Recoded the target variable for Naive Bayes.
Used a 70/30 train-test split with a fixed random seed.
## Tools
##### R
##### ggplot2
##### caret
##### rpart
##### naivebayes
##### dplyr
## Machine Learning Models
##### Decision Tree
##### Naive Bayes
## Techniques
##### Exploratory Data Analysis
##### Feature Visualization
##### Train/Test Split
##### Cross Validation
##### Confusion Matrix
##### Accuracy Evaluation
## Results
The Decision Tree achieved 89.33% accuracy, outperforming the Naive Bayes model (82.33% accuracy). It also achieved substantially higher sensitivity for detecting PCOS cases, making it the stronger model for this dataset.
