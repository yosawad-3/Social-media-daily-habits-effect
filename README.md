📌 Overview

The goal of this project is to build a machine learning model that predicts whether a teenager is experiencing depression based on behavioral, social, and lifestyle factors such as sleep, social media usage, stress levels, and academic performance.

This model helps in:

Identifying early signs of depression
Understanding key behavioral risk factors
Supporting mental health awareness and prevention
📊 Problem Type

Supervised Learning

Specifically:

👉 Binary Classification Problem

Because the target variable (depression_label) has two classes:

0 → Not Depressed
1 → Depressed
🎯 Objectives


Collect and preprocess mental health-related behavioral data
Perform exploratory data analysis (EDA) to understand patterns
Handle class imbalance using appropriate techniques
Train a classification model to predict depression status
Evaluate model performance using proper metrics (Precision, Recall, F1-score)
Identify the most important features affecting mental health


🧠 Model Used

Random Forest Classifier
Handles non-linear relationships well
Works effectively with mixed numerical and categorical features
Robust against noise and overfitting
📈 Evaluation Metrics

The model is evaluated using:

Accuracy
Precision
Recall (very important for depression detection)
F1-score
Confusion Matrix
🛠️ Tech Stack

Languages:

Python

Libraries:

Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

Tools:

Google Colab
Git & GitHub


💻 Contributors


Youssef Mohamed Awad
GitHub: https://github.com/yosawad-3

📌 Key Insights


Lifestyle factors such as sleep hours, social media usage, and stress levels are strong indicators of depression
The dataset is imbalanced, requiring techniques like SMOTE or class weighting
The model achieves strong generalization performance (~92% accuracy on test data)
