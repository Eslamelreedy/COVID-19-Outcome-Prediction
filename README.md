# COVID-19 Outcome Prediction

## Project Description:
The CSAI 801 Project focuses on predicting the outcome (recovery or death) of COVID-19 patients based on predefined standard symptoms. The dataset contains daily-level information on the number of affected cases, deaths, and recoveries from the novel coronavirus. The project utilizes time series data starting from January 22, 2020, and provides a "data.csv" file for analysis.

The dataset consists of 14 variables, including country, location, age group, gender, history of visiting Wuhan, presence in Wuhan, symptoms, time before symptoms appear, and the ultimate outcome (death or recovery). The goal is to design different classifiers to predict the outcome when a new patient is admitted to the hospital.

The project requires dividing the dataset into three partitions: training, validation, and testing. The following classifiers are to be implemented and optimized:

1. K-Nearest Neighbors
2. Logistic Regression
3. Naïve Bayes
4. Decision Trees
5. Support Vector Machines

Optimal hyperparameters will be identified for each classifier. The performance of all classifiers will be compared using various evaluation metrics such as precision, recall, F1-score, and ROC/AUC curves.

The project report should summarize the findings and support the arguments with visualizations. The code files (.ipynb) must be included and uploaded alongside the project report.

