# Employee_turnover_prediction

This project aims to predict employee turnover using historical HR data. Employee turnover, or churn, is a critical metric for any organization as it directly impacts productivity, morale, and ultimately, the bottom line. By leveraging machine learning techniques on historical data, this project aims to provide insights into potential turnover risks, allowing proactive measures to be taken to retain valuable talent.

Dataset
The dataset used in this project contains historical information about employees, including attributes such as:

Employee ID
Age
Gender
Departments
promotion last 5years
left (a Boolean value)
Salary
Work accident (a Boolean value)
time spend company
average montly hours
Number of projects worked on
last evaluation
satisfaction level
Methodology
Data Preprocessing: Clean the dataset, handle missing values, encode categorical variables, and normalize numerical features.
Feature Engineering: Create new features or transform existing ones to enhance predictive power.
Model Selection: Experiment with various machine learning algorithms such as logistic regression, random forest, gradient boosting, etc., to identify the best-performing model.
Model Training: Train the selected model on the preprocessed dataset.
Model Evaluation: Evaluate the model's performance using appropriate metrics such as accuracy, precision, recall, and F1-score. Additionally, analyze the ROC curve and AUC to assess the model's ability to discriminate between classes.
Hyperparameter Tuning: Fine-tune the model parameters to optimize performance.
Prediction: Use the trained model to predict employee turnover for new data.
Requirements
Python 3.x
Jupyter Notebook
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
