Project Overview
This project evaluates supervised and ensemble machine learning techniques on the UNSW-NB15 dataset, a comprehensive dataset for network intrusion detection. The dataset was obtained from Kaggle (https://www.kaggle.com/datasets/dhoogla/unswnb15) and includes labeled records for normal and malicious traffic.

The analysis encompasses preprocessing, exploratory data analysis (EDA), and evaluation of various machine learning models for intrusion detection.

Dataset Information
Files Used:
UNSW_NB15_training-set.csv: Training data
UNSW_NB15_testing-set.csv: Testing data
Attributes: Contains network traffic features, including protocol, service type, source bytes (sbytes), destination bytes (dbytes), attack category (attack_cat), and labels (label).

Steps and Methodology
1. Data Loading and Preprocessing
The training and testing datasets are loaded using pandas.
Missing values are checked and handled.
Numeric features are selected for modeling.
Categorical variables are encoded using LabelEncoder.


2. Exploratory Data Analysis (EDA)
Visualizations include:
Distribution of services.
Scatter plots for sbytes vs dbytes.
Histogram for connection durations (dur).
Bar charts showing the count of different attack categories and labels.


3. Machine Learning Models
Supervised Learning Models
Logistic Regression
Decision Tree Classifier
Naive Bayes
K-Nearest Neighbors (KNN)


4. Ensemble Learning Models
Gradient Boosting
Bagging Classifier
Stacking Classifier
Voting Classifier


5. Metrics Evaluated
Accuracy
Confusion Matrix
ROC Curves


The increasing complexity of cyber threats necessitates advanced techniques for detecting network intrusions. This project explores the performance of supervised and ensemble machine learning models on the UNSW-NB15 dataset, a widely used benchmark for network intrusion detection. The study evaluates multiple models to identify the most efficient techniques for distinguishing between normal and malicious network traffic. Results demonstrate that ensemble learning models, particularly the Bagging Classifier and Stacking Classifier, outperform traditional supervised learning models in terms of accuracy, achieving up to 96% accuracy on test data. These findings emphasize the potential of ensemble approaches in enhancing network security.
