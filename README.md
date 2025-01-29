The goal is to create a predictive model that can effectively distinguish between HIV-positive and HIV-negative individuals to enable early diagnosis and intervention.
Dataset Information
Source of the dataset is kaggle.

* steps followed:
a.Data import and shaped, 
b.EDA, 
c.Data cleaning, 
d.Class balancing,
e.Model building and evaluation, 
f.Feature importance,
g.Boosting algorithms,
h.Hyper parameter tunning 

* Data preprocessing steps are:-
Exaploratory Data Analysis is performed such as,
Missing values detection
Finding duplicates
Identification and handling of outliers 
Visualize the distribution of numerical features
Exlporing about categorical variables
Finding relationship between features & target variable

* Model & Methodology
Algorithms Used:
Random Forest and Logistic Regression

* Evaluation Metrics:
Accuracy, Precision, Recall, F1-score

* Hyper parameter tunning models
 Boosting algorithms used: Cat Boost Classifier, XGB Classifier

* Comparison Of All Models

*    Algorithm              Accuracy  Precision  Recall  F1 Score
1  Logistic Regression       0.64       0.79     0.66      0.72
2  Random Forest             0.98       0.97     0.94      0.96
3  Decision Tree             0.97       0.97     0.95      0.96

* Conclusion:
The Random Forest model, with a accuracy of 98% , outperforms other models, showcasing its balanced performance, robustness, flexibility, and feature importance insights,
making it the optimal choice for accurate and reliable predictions. Based on the evaluation results, we recommend using the Random Forest model for predicting whether a patient is
having AIDS infection or not having infection. Its superior performance across all metrics makes it the most suitable choice for this prediction task.
