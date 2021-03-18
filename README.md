# Predict_the_Insurance_Claim_using_Logistic_Regression

Problem statement:
Till now you have seen that how to solve the linear regression and regularization problem. Now in this project, you are going to predict the Insurance claim using logistic regression. This dataset contains information on the insurance claim. each observation is different policyholders with various features like the age of the person, the gender of the policyholder, body mass index, providing an understanding of the body, number of children of the policyholder, smoking state of the policyholder and individual medical costs billed by health insurance.

The dataset has details of 1338 Insurance claim with 8 features. You need to predict the Insurance Claim (Yes:1/No:0)

About the dataset
A zipped file containing the following items is given:

train.csv
The data file train.csv contains the 1070 instances with the 8 features including the target feature.

test.csv
The datafile test.csv contains the 268instances with the 7 features excluding the target feature.

sample_submission.csv
Explained under the Submission sub-heading

LogisticDataDictionary.csv
The file contains data dictionary(Dictionary explaining what each feature of the dataset means) of the Insurance Claim dataset

logistic_regression_student_template.ipynb
A template notebook explaining the task breakdown to solve the given problem statement (Learners are recommended to use it)

Submission
After training the model on train.csv data, the learner has to predict the target feature of the test.csv data using the trained model. The learner has to then submit a csv file with the predicted feature.

Sample submission file(sample_submission.csv) is given to you as a reference to the format expected when you submit

Evaluation metrics
For this particular dataset we are using roc_auc_score as the evaluation metric.

Submissions will be evaluated based on ROC-AUC score as per the below threshold.

Your roc_auc_score score	Points earned for the Task
0.91 <= roc_auc_score	100% of the available points
0.89 <= roc_auc_score < 0.91	80% of the available points
0.85 < roc_auc_score < 0.89	70% of the available points
roc_auc_score <= 0.85	No points earned
Outcomes
The main objective of this task is to provide you with an open field where you can practice and work your way with a dataset end to end without any restrictions from our side. So feel free to play around the model until you arrive at your best solution.

In this project, you will apply the following concepts:

EDA & Data Preprocessing
Correlation between the features
Model Building using Logistic Regression
After completing this project, you will have a better understanding of how to build a logistic regression model.

Skills Covered:
Logistic Regression
sklearn
data cleaning
