Breast Cancer Classification using Naive Bayes

Overview

This project implements a Naive Bayes classifier to predict whether a tumor is malignant or benign based on given features. The model is trained and evaluated using a dataset containing various tumor characteristics.

Process

Data Loading:

The dataset is read from a CSV file.

Unnecessary columns (such as id and unnamed columns) are dropped.

The target variable (diagnosis) is encoded as 1 for malignant and 0 for benign.

Data Preprocessing:

Features (X) and target (y) variables are separated.

The dataset is split into training (80%) and testing (20%) sets.

Feature scaling is applied using StandardScaler to normalize the dataset.

Model Training:

A Naive Bayes classifier (GaussianNB) is used to train the model.

The model learns patterns from the training data.

Model Evaluation:

Predictions are made on the test data.

Performance metrics such as accuracy, confusion matrix, and classification report are computed.

A heatmap visualization of the confusion matrix is generated for better interpretation.

Architecture

Input: Breast cancer dataset (CSV file)

Processing:

Data cleaning and preprocessing

Feature scaling

Training with Naive Bayes classifier

Output: Model predictions and evaluation metrics

Tools and Frameworks Used

Programming Language: Python

Libraries:

pandas - for data manipulation

numpy - for numerical computations

matplotlib & seaborn - for visualization

sklearn (Scikit-learn) - for machine learning algorithms and model evaluation

Results

Accuracy: ~96.49%

Confusion Matrix:

True Positives: 40

True Negatives: 70

False Positives: 1

False Negatives: 3

Classification Report:

Precision, recall, and F1-score indicate a high-performance model.

The Naive Bayes classifier performed well in distinguishing between benign and malignant tumors with high accuracy and minimal misclassifications. This approach provides a simple yet effective method for breast cancer detection.


![image](https://github.com/user-attachments/assets/1279c705-5d20-4eab-b28c-6b382248ba5f)
