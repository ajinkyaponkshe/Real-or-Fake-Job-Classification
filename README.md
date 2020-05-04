# Real-or-Fake-Job-Classification

## Goal
Classify Real or Fake job applications

## Data Shape
rows: 17880, columns: 17 

## Missing Data
Total missing values in the dataset are 27.84%

## Models Used
### Basic Algorithms
1.	Logistic Regression
2.	Decision Tree
3.	k-Nearest Neighbors
5.	Support Vector Machine
6.	Random Forest
7.	Extra Trees
8.	Gradient Boosting
9.	XgBoost
10.	Stacking Classifiers

### 	Data Sampling Algorithms (using SMOTE)
11.	Logistic Regression
12.	Decision Tree
13.	k-Nearest Neighbors
14.	Support Vector Machine
15.	Random Forest
16.	Easy Ensemble Classifier
17.	XgBoost
18.	Stacking Classifiers

## Final Model

Best Model: XGBoost Classfier

Best Mean Cross Validation Score is 0.9577 Best Mean Cross Validation Score is {'learning_rate': 0.5, 'max_depth': 6, 'min_child_weight': 1, 'n_estimators': 100, 'subsample': 0.7} Train score is 0.9688 Test score is 0.9666
