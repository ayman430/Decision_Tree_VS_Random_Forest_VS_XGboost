# Decision_Tree_VS_Random_Forest_VS_XGboost
# project definition 
- You have some medical analyzes related to the respiratory system, heart performance, and pressure and want to know if he has a "Heart Disease" or not 
- Using 3 models to compare which has best performance

## Tools used 
- numpy 
- pandas
- matplotlib
- sklearn
- xgboost

## Data set from Kaggle 
[Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

## Objectives
- Loading the data
- Encoding catigorical columns using pd.get_dummies
- Spliting data to trainning data and test data
- Decision Tree model 
    - Find hyperparameters min_samples_splits and max_depth using visualize relationship between accuracy and  change of each of them 
    - Training and test model
    
- Random Forest model
     Find hyperparameters min_samples_splits, max_depth and n_estimators using visualize relationship between accuracy and  change of each of them 
    - Training and test model
- XGBoost model
  - Finding best_iteration
  
## Comparing models using Accuracy_score and find :
1- Decision Tree
- Training Accuracy score: 0.8665
- Testing Accuracy score : 0.8696
  
2- Random Forest
- Training Accuracy score: 0.9319
- Testing Accuracy score : 0.8913
  
3- XGBoost
- Training Accuracy score: 0.9673
- Testing Accuracy score : 0.8859

# Conclusion
Comparing 3 models find high impact of ensamble techniques find random forest and xgboost extremely close in testing which reflecting importace of bagging and boosting in increasing preformace .



















































