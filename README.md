# Credit_Risk_Analysis

## Supervised Machine Learning

Credit risk analysis is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We will need to employ different techniques to train and evaluate models with unbalanced classes. We will use imbalanced-learn and scikit-learn libraries to buil and evaluate models using resampling. And also we oversample the data using the RandomOverSample and SMOTE algorithms, and undersample the data using the ClusterCentroids.

## Resources

•	Software: Jupyter Notebook
•	Languages: Python
•	Libraries: Scikit-learn
•	Environment: Python 3.7

## Result
### 1.Naïve Random Oversampling
•	Accuracy score: 0.50
•	Precision high risk score is only 0.33and low risk score is 0.99
•	Recall score for hight risk is at 0.01 and low risk at 1

<img width="653" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/77603561/179919889-bd71d251-5f9f-4e0b-8c62-1e1cad00d83f.png">

### 2.SMOTE
•	Accuracy score: 0.50
•	Precision high risk score is only 0.33and low risk score is 0.99
•	Recall score for hight risk is at 0.01 and low risk at 1

<img width="650" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/77603561/179919912-0f5af4e0-a8ca-489e-9b34-494efce90d12.png">

### 3.Cluster Centroids
•	Accuracy score: 0.67
•	Precision high risk score is only 0.01 and low risk score is 1
•	Recall score for hight risk is at 0.72 and low risk at 0.61

<img width="644" alt="Cluster Centroids" src="https://user-images.githubusercontent.com/77603561/179919936-679de892-39e3-4343-b8b6-fcb33a2be339.png">

### 4. SMOTEENN and Logistic Regression
•	Accuracy score: 0.55
•	Precision high risk score is only 0.01 and low risk score is 1
•	Recall score for high risk is at 0.67 and low risk at 0.43

<img width="653" alt="SMOTEEN and Logistic Regression" src="https://user-images.githubusercontent.com/77603561/179919961-71c0e9d6-7dd7-4f6b-8030-b6719f2e3bd7.png">

### 5. Balanced Random Forest Classifier
•	Accuracy score: 0.77
•	Precision high risk score is only 0.03 and low risk score is 1
•	Recall score for high risk is at 0.66 and low risk at 0.88

<img width="647" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/77603561/179919988-3691b4a5-be17-41c5-9db5-515147e3f0cb.png">

### 6. Easy Ensemble AdaBoost Classifier
•	Accuracy score: 0.93
•	Precision high risk score is only 0.09 and low risk score is 1
•	Recall score for high risk is at 0.92 and low risk at 0.94

<img width="655" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/77603561/179920001-dbd99d34-0684-4943-88d3-cb8cc7974959.png">

## Summary

For first 4 models result 0.50, 0.50, 0.55 meaning the models were accurate roughly a bit more than half of time.

Last two models did better than other ones.Scores are 0.79 and 0.93. so we can recommend these models instead of first four models.












