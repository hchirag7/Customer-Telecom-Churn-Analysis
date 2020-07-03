# Customer-Telecom-Churn-Analysis
Implemented Machine Learning models including Classification, Ensemble Learning, Dimension Reduction and Deep Learning; for 51K Customer data with 58 Features
<hr>

## Project Highlights
1. Implemented data preprocessing on 51000 customer data with 58 features & used classification models like Random Forest, Support Vector Machine for churn classification.
2. Applied models to improve performance like bagging, boosting, PCA dimensionality reduction.
3. Classified likeliness of a customer to churn or not with 93% accuracy using best parameters by Grid Search CV and Cross Validation
<hr>

## Introduction & Scope
**Link** : https://www.kaggle.com/jpacse/datasets-for-churn-telecom*

**Description** :  Telecommunication companies face a problem of churning of their customers for other companies. In this dataset,we look at different scenarios in which customers are most likely to leave their current company. 
    
**Initial Analysis**:  Dataset is supposed to have few missing values and some pre-processed columns. These columns will first be converted to view their original data and processed as per teachings of the course.

**Project Objective : Project 1** : Data has attributes like MonthlyRevenue, MonthlyMinutes, ThreewayCalls, OverageMinutes, BlockedCalls,DropedCalls. These features might correspond to whether a customer will churn or not. Our objective is to:
* Initializations: Process data correctly to reflect right data impute missing values if required
* Preprocessing: Preprocess data for our machine learning models
* Data Visualization
* Apply ML Classification Models:
  1. KNN Classifier
  2. Logistic Regression
  3. LinearSVC
  4. Kernalized SVC (linear, rbf, poly)
  5. DecisionTree
* GridSearchCV for best parameters
* Cross-Validaiton to find average training and test scores
* Best Classifier with best parameters

**Project Objective : Project 2** : We'll continue implementing new algorithms and adding to main comparison table for accuracy. We'll apply PCA and reiterate previously run models for checking improvement in accuracy. Focussed implementation includes:
* Applying two voting classifiers - one with hard voting and one with soft voting
* Applying any two models with bagging and any two models with pasting.
* Applying any two models with adaboost boosting
* Applying one model with gradient boosting
* Applying PCA on data and then apply all the models in project 1 again on data you get from PCA. Comparing our results with  results in project 1.
* Apply deep learning models covered in class
