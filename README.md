Telecom-Customer-Churn-Prediction
Project Overview
This project involves predicting customer churn for a telecom company using machine learning models. The goal is to analyze customer behavior and predict whether a customer will leave the service based on various features such as customer demographics, service usage, contract type, and account information.

Techniques Used:
Logistic Regression: A binary classification model used to predict the likelihood of a customer churning.

K-Nearest Neighbors (KNN): A non-parametric method for classification based on proximity.

Support Vector Machine (SVM): A powerful classification algorithm used to identify the decision boundary between churned and retained customers.

Data Description
The dataset used in this project is the Telecom Customer Churn Dataset. It contains customer data with various attributes related to account information, services used, and customer demographics. The target variable indicates whether a customer has churned or not.

Key Features:
CustomerID: Unique ID for each customer.

Gender: Gender of the customer.

SeniorCitizen: Whether the customer is a senior citizen (1 = Yes, 0 = No).

Partner: Whether the customer has a partner (Yes/No).

Dependents: Whether the customer has dependents (Yes/No).

Tenure: Number of months the customer has been with the company.

Service: Type of services subscribed (e.g., Phone Service, Internet Service).

Contract: Type of customer contract (e.g., Month-to-Month, One-Year, Two-Year).

MonthlyCharges: Monthly charges for the customer.

TotalCharges: Total charges the customer has incurred.

Churn: Target variable indicating if the customer churned (0 = No, 1 = Yes).

Objectives:
Objective 1: Analyze the impact of customer demographics on churn probability.

Objective 2: Evaluate the influence of customer tenure and contract type on retention.

Objective 3: Explore the relationship between service types and churn likelihood.

Objective 4: Investigate how monthly and total charges affect customer retention.

Objective 5: Examine the performance of various machine learning models in predicting churn.

Data Preprocessing:
Before applying machine learning models, the following preprocessing steps were performed:

Removed unnecessary columns like CustomerID for model training.

Handled missing values where applicable.

Encoded categorical variables (Gender, Partner, Dependents, Contract, etc.) using Label Encoding and One-Hot Encoding.

Normalized numerical features using StandardScaler to improve model performance.

Split the dataset into training and testing sets.

Machine Learning Models:
The project applies three different machine learning models to predict customer churn:

Logistic Regression: A binary classification model for predicting the likelihood of a customer churning.

K-Nearest Neighbors (KNN): A classification algorithm that uses proximity to classify customers.

Support Vector Machine (SVM): A powerful classification model used to predict churn.

Each model is evaluated using accuracy, confusion matrix, and classification report.

Contributing:
Feel free to fork this repository, make improvements, and submit pull requests. Contributions, suggestions, and feedback are always welcome!
