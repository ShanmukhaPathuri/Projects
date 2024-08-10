Thyroid Classification Using SAS & Tableau Project 🩺🔍

Welcome to my GitHub! I'm Shanmukha Venkata Sai Kiran Pathuri, and this repository showcases one of my key projects - Thyroid Classification Using Machine Learning. This project aims to accurately classify thyroid diseases using SAS for machine learning and Tableau for visualization.

📝 Project Overview
Introduction: 
Thyroid diseases are disorders that affect the thyroid gland, with two major categories: hypothyroidism and hyperthyroidism. In this project, I developed a machine learning model to classify thyroid conditions accurately, aiding in early diagnosis and better treatment outcomes.

Problem Statement: 
By analyzing patient data like medical history and blood tests, machine learning can be leveraged to diagnose thyroid conditions more accurately. The primary goal is to create a model that can classify thyroid diseases into four categories: hyperthyroid, hypothyroidism, and negative.

Project Aim: 
The project uses machine learning techniques with SAS for data processing and visualization via Tableau. The aim is to accurately classify thyroid diseases and provide insights that help healthcare professionals make informed decisions.

🛠️ Tools and Technologies 

Programming Languages: SAS, Tableau
Machine Learning Techniques: Decision Trees, Logistic Regression
Visualization: Tableau

🧠 Methodology

Data Collection and Preprocessing: 
The dataset used includes 9172 observations with attributes like age, gender, and thyroid-specific tests.
Missing data was imputed using median values.
Data was reduced by removing insignificant columns, ensuring only relevant features were used for modeling.

Modeling:

Decision Tree: Multiple decision trees with varying depths and branches were trained to optimize classification accuracy.
Logistic Regression: Applied forward logistic regression, though decision trees outperformed this model in terms of accuracy.

Evaluation:

The models were evaluated based on misclassification rates, with the decision tree achieving the best performance with a minimum misclassification rate.

📊 Key Findings

Significant Variables: TSH, TT4, FTI, and T3 were identified as the most crucial variables for thyroid classification.
Model Performance: Decision trees provided better accuracy compared to logistic regression, highlighting the importance of tree-based models for this problem.
Visualization Insights: Most patients belong to the "concurrent non-thyroidal illness" category, with older patients showing a higher prevalence of certain thyroid conditions.

🚀 Future Work

Improving Model Accuracy: Implementing neural networks could enhance the classification accuracy further.
Data Expansion: Including more male patients and balancing the dataset for better generalization.
Boosting Techniques: Applying boosting methods to improve model performance beyond logistic regression.

🏆 Lessons Learned

The critical role of data preprocessing and feature selection in building effective machine learning models.
The importance of model evaluation to avoid overfitting, especially in decision trees.
