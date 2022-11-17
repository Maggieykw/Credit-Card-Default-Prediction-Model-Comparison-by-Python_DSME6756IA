# Credit-Card-Default-Prediction-Model-Comparison-by-Python_DSME6756IA

### Objective: 
Predicting the credit card default by using client information

### Dataset: 
- Source: Kaggle (https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)
- 30,000 records of credit card clients in Taiwan during April-October 2005
- 25 variables:
  - 24 independent variables 
  (e.g. demographic information, repayment status, historical payment, bill amount)
  - 1 dependent variable (credit card default in October 2005)

### Project Summary
There are three main parts:
1. Dataset Exploration
2. Data Cleaning
3. Modelling

#### Dataset Exploration:
Plotting different tables/graphs to allow us to get familiar with the dataset, for example, missing value, correlation matrix, repayment status during April-September 2005, age distribution, education distribution, gender distribution and so on.

#### Data Cleaning:
- Removing some column(s) that are not useful for modelling
- Renaming some column(s) for easy reference
- Fixing abnormal value (e.g. undocumented/unlabeled value)
- Minimize the modelling error due to imbalanced class by oversampling technique (i.e. SMOTE (Synthetic Minority Oversampling Technique))

#### Modelling:
- Build 15 quick predictive models by PyCaret
- Pick up three models for further investigation and fine-tuning. The models are logistic regression, decision tree and XGBoost
- Select the optimal hyperparameters for the above 3 models
- Evaluate the model performance
- Select the best predictive model as the final model


