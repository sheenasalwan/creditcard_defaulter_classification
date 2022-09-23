# Credit Card Defaulter Classification
Classification problem to predict the credit card holder defaulter behaviour

## Pipeline followed:
1. Understanding the Problem:
  - goal of the problem
  - identifying the target variable
  - size of dataset
  - type of features
  - identify type of problem - classification/regression
  - identify type of classification - binary/multi-class
2. Data Splitting
    - train test split
3. Exploratory Data Analysis (EDA)
    - check summary statistics(data type of features, min/max values)
    - check for missing values
    - check for colinearility, scaling, data outliers via visualization
    - check for class imbalance and identify the metrics for assessment
### Preprocessing and transformations
  - one-hot encoding, scaling, ordinal, binary
  - make pipeline
  - column tranformer
#### Baseline Model
  - Dummy Classifier
#### Linear Models
  - LogisticRegression, with class weights, SMOTE
  - pick one and perform Hyperparameter Optimization
#### Different Classifiers
  - Try different models
    - SVM
    Tree based models:
    - Random Forest
    - XGBoost
    - LGBM
  - check for overfitting, underfitting
  - pick best models for further hyperparameter optimization
#### Feature Selection
  - Recursive feature elimination 
#### Hyperparamter Optimization
  - GridSearchCV/RamdomSearchCV
  - Check fit time, train and validation scores
  - pick the best estimator
#### Interpretation and feature importance
  - feature_importance_
  - eli5
  - SHAP
#### Results on test set
  - check results with best estimator
  - check consistency with validation scores
  - check for optimization bias
  - Interpret predictions - confusion matrix, classification report, SHAP
  