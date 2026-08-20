Problem Set 1 - Bank Marketing Prediction
Problem Statement
A banking institution wants to predict whether a customer will subscribe to a term deposit or not based on their banking behaviour.

For this problem, Logistic Regression is used to classify customers into two categories:

Yes - Customer subscribed to a term deposit
No - Customer did not subscribe to a term deposit
Dataset
The dataset used is the Bank Marketing Dataset.

The dataset contains information about bank customers, including:

Age
Job
Marital Status
Education
Account Balance
Housing Loan
Personal Loan
Contact Type
Campaign Information
Previous Contact Information
Previous Campaign Outcome
Term Deposit Subscription
Dataset file:

bank-full.csv

The dataset contains 45,211 customer records and 17 attributes.

Technologies Used
Python
Pandas
Matplotlib
Scikit-learn
Google Colab
Machine Learning Algorithm
Logistic Regression
Logistic Regression is a supervised machine learning algorithm used for classification problems.

In this project, Logistic Regression is used to predict whether a customer will subscribe to a term deposit.

Data Preprocessing

The following preprocessing steps were performed:

Loaded the dataset using Pandas.
Converted categorical values into numerical values using LabelEncoder.
Separated the features (X) and target variable (y).
Split the dataset into training and testing sets.
Standardized the features using StandardScaler.
Train-Test Split

The dataset was divided into:

80% Training Data
20% Testing Data
Model Training

A Logistic Regression model was created using Scikit-learn.

The model was trained using the training dataset and then used to predict the target values of the testing dataset.

Evaluation Metrics

The model was evaluated using:

Accuracy
Confusion Matrix
Classification Report
Precision
Recall
F1-Score
