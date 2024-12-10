# Credit-Card-Fraud-Detection
This project focuses on detecting fraudulent credit card transactions using a Logistic Regression model. With the rapid growth of online transactions, identifying fraudulent activities is crucial for financial security. The project leverages machine learning techniques to achieve high accuracy in detecting fraud.

Objective
To develop a robust machine learning model that can:

Detect fraudulent credit card transactions.
Handle the imbalanced nature of the dataset effectively.
Provide actionable insights using metrics like Precision, Recall, and AUC-ROC.
Dataset
The dataset used for this project is sourced from the Kaggle Credit Card Fraud Detection dataset. It contains transactions made by European cardholders in September 2013.

Dataset Features
Rows: 284,807 transactions.
Columns: 31 (28 anonymized features, Time, Amount, and Class).
Class: The target variable (0 = Not Fraud, 1 = Fraud).

Steps and Methodology
1. Exploratory Data Analysis (EDA)
Visualized class distribution to understand data imbalance.
Explored relationships between features using correlation heatmaps.
Identified outliers using boxplots.

3. Data Preprocessing
Standardized numerical features (StandardScaler).
Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique).
Split data into training (70%) and testing (30%) sets.

5. Model Building
Built a Logistic Regression model for binary classification.
Tuned the decision threshold for optimizing Recall and Precision.

7. Evaluation Metrics
Used metrics suited for imbalanced data:
Precision: Focus on reducing false positives.
Recall: Ensure minimal false negatives.
AUC-ROC: Assess overall model performance.
