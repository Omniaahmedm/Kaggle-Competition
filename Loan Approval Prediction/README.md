# Loan Approval Prediction


## Table of Contents
- Goal
- Data Preprocessing
- Exploratory Data Analysis
- Data Splitting
- Model Selection
- Model Training
- Model Evaluation
- Hyperparameter Tuning

## Goal
 - The goal for this competition is to predict whether an applicant is approved for a loan.

## Data Preprocessing
 - Clean and preprocess the data by handling missing values and drop the Outliers.

## Exploratory Data Analysis
- Examine the distribution of the target variable, which is typically whether a loan was approved or denied. Creating a bar plot or pie chart to visualize the 
   distribution etc.
- Explore the distribution of individual features, both numerical and categorical. Use histograms, box plots, or bar charts to visualize the data. Identify outliers using box plots.

## Data Splitting
- Split your data into training and validation sets to evaluate your model's performance.

## Model Selection
- Choose an appropriate machine learning algorithm. I have used common algorithms for this binary classification problem like Logistic Regression, Random Forests, 
  Support Vector Machines and XGBoost.

## Model Training
- Train your chosen model on the training data.

## Model Evaluation
- To evaluate the model's performance I have used area under the ROC curve using the predicted probabilities and the ground truth targets.

## Hyperparameter Tuning
- Optimize the model's hyperparameters to improve its performance. This can be done through techniques like grid search or random search. Grid Search method has 
  been applied in this problem.

**Result:**
   The project achieves an accuracy of around 0.96 using a Bagging with XGBoost model. Further improvements can be made by feature engineering and exploring 
    different algorithms.
