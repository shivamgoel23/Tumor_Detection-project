# Tumor_Detection-project

🧬 Tumor Detection using Machine Learning

📌 Problem Statement

As part of Module 14, this project focuses on developing a Tumor Detection Model that classifies tumors as malignant (M) or benign (B) using machine learning algorithms in Python.

The project evaluates your ability to:

Handle and preprocess medical datasets

Perform Exploratory Data Analysis (EDA)

Build and evaluate classification models

Visualize data patterns and model outcomes

You will work with a Tumor_Detection dataset containing tumor characteristics such as mean radius, texture, perimeter, area, and smoothness.

🎯 Objective

To build a machine learning model that accurately predicts whether a tumor is benign or malignant based on the provided features, and to analyze key factors influencing tumor classification.

⚙️ Approach
1. Data Understanding

The dataset contains numeric features describing various tumor cell properties.

The target variable indicates whether the tumor is:

M → Malignant (Cancerous)

B → Benign (Non-cancerous)

2. Data Preprocessing

Imported and inspected dataset using pandas.

Checked for and handled missing/null values.

Encoded categorical labels (M, B) into numeric format (1, 0).

Performed feature scaling to normalize values for better model performance.

Split data into Training (80%) and Testing (20%) sets.

3. Exploratory Data Analysis (EDA)

Used matplotlib and seaborn to visualize:

Feature distributions

Correlation heatmap

Pair plots to observe class separation

Identified relationships between tumor characteristics and diagnosis.

Key insight: Larger mean radius, higher texture, and perimeter values are often associated with malignant tumors.

4. Model Building

Implemented and compared multiple supervised learning algorithms:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Each model was trained and tested to identify the best performer.

5. Model Evaluation

Evaluated models using the following metrics:

Accuracy

Precision

Recall

F1-score

ROC-AUC score

Visualized:

Confusion Matrix to evaluate prediction results

ROC Curve to assess model discrimination ability

6. Model Optimization

Performed hyperparameter tuning using GridSearchCV to optimize model performance.

Selected the best-performing model based on cross-validation scores and generalization capability.

📊 Key Findings

Random Forest Classifier achieved the highest accuracy (~97%).

Texture, perimeter, and mean radius were the most influential features in classifying tumors.

The model demonstrated high sensitivity, making it reliable for medical diagnostic assistance.

🧠 Technologies Used

Language: Python

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

Environment: Google Colab
