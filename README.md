# Fake Job Posting Detection using Machine Learning

This project develops a Machine Learning-based system to detect fraudulent job postings using Natural Language Processing (NLP). The model analyzes textual information such as job title, company profile, job description, requirements, and benefits to classify job postings as **Legitimate** or **Fraudulent**.

The project includes complete data preprocessing, exploratory data analysis, TF-IDF feature extraction, model training, hyperparameter tuning, and a prediction system.

# Problem Statement

Online job portals contain thousands of job advertisements, but some of them are fake and intended to scam job seekers. Detecting fraudulent job postings manually is difficult and time-consuming.
This project aims to automatically classify job postings into:
- Legitimate Job
- Fraudulent Job
using Machine Learning and Natural Language Processing.

# Dataset
Dataset Name:
Fake Job Postings Dataset
Source:
https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction
Total Records:
17,880
Target Variable:
fraudulent
0 → Legitimate Job
1 → Fraudulent Job

# Features Used
- Title
- Company Profile
- Description
- Requirements
- Benefits
These textual features were merged into a single feature and converted into numerical vectors using TF-IDF.

# Project Workflow

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Missing Value Handling
4. Text Cleaning
5. Feature Selection
6. TF-IDF Vectorization
7. Train-Test Split
8. Model Training
9. Hyperparameter Tuning
10. Model Evaluation
11. Model Comparison
12. Prediction System
13. Model Saving

# Machine Learning Models

- Logistic Regression
- Linear SVM
- Decision Tree
- K-Nearest Neighbors (KNN)
- Multinomial Naive Bayes

# Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

# Results
Among all evaluated models, **Linear SVM** achieved the best overall performance.

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

# Author
Anveshi Srivastava

# LinkedIn:
https://www.linkedin.com/in/anveshi-srivastava-582612297/

# GitHub:
https://github.com/Anveshi-2711-hub
