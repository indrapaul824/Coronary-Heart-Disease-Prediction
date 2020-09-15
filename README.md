# Coronary-Heart-Disease-Prediction
This contains the Jupyter Notebook and the Dataset for the mentioned Classification Predictive Modeling Project


### About the dataset:

The "Framingham" dataset is publically available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,240 records and 15 attributes.

### Objective: To build a classification model that predicts heart disease in a subject. (note the target column to predict is 'TenYearCHD' where CHD = Coronary heart disease) 

### I have performed the following steps: 

1. Read the file and displayed its columns.
2. Handled missing values, Outliers and Duplicate Data.
3. Calculated basic statistics of the data (count, mean, std, etc), did exploratory analysis and described my observations.
4. Resampled the imbalanced dataset by oversampling the positive cases.
5. Selected columns that will probably be important to predict heart disease.
6. Created training and testing sets (using 60% of the data for the training and reminder for testing) and scaled the data using MinMaxScaler.
7. Built 5 different machine learning models to predict TenYearCHD:
    a. Logistic Regression - 67.56% Accuracy
    b. kNN Classification - 89.98% Accuracy
    c. Random Forest Classification - 90.39% Accuracy
    d. Decision Tree Classification - 86.66% Accuracy
    e. Gradient Boosting Classification - 71.46% Accuracy
8. Hyperparameter tuned the RandomForestClassification - 95.77% and GradientBoostingClassification - 95.21%.
9. Evaluated each model (f1 score, Accuracy, Precision ,Recall and Confusion Matrix) and plotted a graph for the false positive rate and true positive rate for each model.
10. Ensembled the four best models using Stacking technique to further increase the accuracy of the model and achieved an accuracy score of 96.17%
11. Concluded that Ensembling all the four most important models, with Random Forest Classification leading the way, has resulted in a very high accuracy score.



