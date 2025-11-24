#  Wizardry-School-Admission-Prediction-ML-Classification

Machine learning project developed for the **Machine Learning I (NOVA IMS)** course.  
The goal was to build a **predictive model** capable of determining whether a student would be admitted to a *school of magic* based on their profile and background. 

## Overview
- Binary **classification** problem (admitted vs. rejected)
- Dataset of **713 student applications**
- Mix of **categorical** and **numerical** features
- Models tested included Logistic Regression, Decision Trees, KNN, Naive Bayes, Neural Networks, Random Forests, Boosting, and **Stacking**

## Approach
- Exploratory data analysis & handling of missing values  
- One-hot encoding of categorical features  
- Feature selection using **RFE** and **Lasso**  
- Hyperparameter tuning with **GridSearch** and **RandomizedSearch**  
- Evaluation using metrics:**accuracy**, **precision**, **recall**, **F1-score**, and **Kaggle score**

## Best Model
The **Stacking Classifier** achieved the best overall performance, outperforming individual models in F1-score and Kaggle evaluation.
