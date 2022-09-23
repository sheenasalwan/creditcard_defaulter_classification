# Credit Card Defaulter Classification
Classification problem to predict the credit card holder defaulter behaviour

## Pipeline followed:
  ### Understanding the Problem:
      1. goal of the problem
      2. identifying the target variable
      3. size of dataset
      4. type of features
      5. identify type of problem - classification/regression
      6. identify type of classification - binary/multi-class
        
### Data Splitting
  - train test split
        
### Exploratory Data Analysis (EDA)
    - check summary statistics(data type of features, min/max values)
    - check for missing values
    - check for colinearility, scaling, data outliers via visualization
    - check for class imbalance and identify the metrics for assessment
        
4. Preprocessing and transformations
  - one-hot encoding, scaling, ordinal, binary
  - make pipeline
  - column tranformer
5. Baseline Model
  - Dummy Classifier
6. Linear Models
  - LogisticRegression, with class weights, SMOTE
  - pick one and perform Hyperparameter Optimization
7. Different Classifiers
  - Try different models
    - SVM
    Tree based models:
    - Random Forest
    - XGBoost
    - LGBM
  - check for overfitting, underfitting
  - pick best models for further hyperparameter optimization
8. Feature Selection
  - Recursive feature elimination 
9. Hyperparamter Optimization
  - GridSearchCV/RamdomSearchCV
  - Check fit time, train and validation scores
  - pick the best estimator
10. Interpretation and feature importance
  - feature_importance_
  - eli5
  - SHAP
11. Results on test set
  - check results with best estimator
  - check consistency with validation scores
  - check for optimization bias
  - Interpret predictions - confusion matrix, classification report, SHAP
  