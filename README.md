# CREDIT RISK ANALYSIS

## OVERVIEW

### The challenge given is a real world challenge: apply machine learning to solve credit card risk issues.

### Credit Risk is an inherently unbalanced classification problem, as good loans easily out number risky loans.  Different techniques will need to be employed to train and evaluate models using Resampling and Ensemble.


## RESOURCES

### File: LoanStats_2019Q1.csv (from LendingClub)

### mlenv - Environment: machine learning environment

### numpy

### pandas

### pathlib

### collections

### sklearn.model_selection   train_test_split

### imblearn.over_sampling    RandomOverSampler

### sklearn.linear_model    Logistic Regression

### sklearn.metrics   balanced_accuracy_score

### sklearn.metrics   confusion_matrix

### lmblearn.metrics    classificiation_report_imbalanced

### imblearn.over_sampling    SMOTE

### imblearn.under_sampling   ClusterCentroids

### imblearn.combine    SMOTEENN

### imblearn.ensemble   BalancedRandomForestClassifier

### imblearn.ensemble   EasyEnsembleClassifier

## RESULTS

### Credit Risk Resampling Techniques

### Process:

1) Read the csv and perform basic data cleaning.

2) Split the data into training data and testing data.

3) Compare oversampling algorithms to determine which provides the best performance

Algorithm 1 - Naive Random Oversampling

Accuracy Score for the model:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/11.png)

Confusion Matrix:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/12.png)

Imbalance Classification Report:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/13.png)

Algorithm 2 - SMOTE Oversampling

Accuracy Score for the model:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/16.png)

Confusion Matrix:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/17.png)

Imbalance Classification Report:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/18.png)

4) Test an undersampling algorithm to determine which has the best performance compared to oversampling.

Algorith - Cluster Centroids

Confusion Matrix:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/22.png)

Imbalance Classification Report:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/23.png)

5) Test using a combination of (Over and Under) Sampling

Algorithm - SMOTEENN

Accuracy Score for the model:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/26.png)

Confusion Matrix:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/27.png)

Imbalance Classification Report:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/28.png)

### Credit Risk Ensemble

### Process:

1) Read the csv data and perform basic data cleaning.

2) split the data into training and testing.

3) Compare two ensemble algorithm to determine which results in the best performance.

Algorithm 1 - Balanced Random Forest Classifier

Accuracy Score for the model:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/2_11.png)

Confusion Matrix:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/2_12.png)

Imbalance Classification Report:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/2_13.png)

The features are sorted in descending order by feature importance:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/2_14.png)

Algorithm 2 - Easy Ensemble Adaboost Classifier

Accuracy Score for the model:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/2_16.png)

Confusion Matrix:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/2_17.png)

Imbalance Classification Report:

![__](https://github.com/Johnnytoobadman/Credit_Risk_Analysis/blob/main/Images/2_18.png)



## SUMMARY



