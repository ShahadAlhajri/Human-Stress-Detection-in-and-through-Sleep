
# Automated Stress Detection System



## Overview



This project aims to develop an automated system for detecting and quantifying stress levels using physiological data and machine learning algorithms. Traditional stress assessment methods often rely on subjective self-reporting, which can be unreliable. Our solution leverages data from wearable sensors to provide an objective measure of stress, helping individuals and healthcare professionals manage stress effectively.



## Objectives



1. **Data Collection:** Gather physiological data from individuals during various stress-inducing scenarios.

2. **Model Implementation:** Classify individuals into stress levels (0 - low/normal, 1 - medium low, 2 - medium, 3 - medium high, 4 - high) using machine learning models.

3. **Performance Evaluation:** Compare different classification algorithms to identify the most effective approach for stress detection.

4. **Result Analysis:** Analyze and interpret the results to understand their effectiveness and impact.



## Dataset



We utilized the "Human Stress Detection in and through Sleep" dataset from Kaggle, which contains 630 rows of physiological data collected during sleep. The dataset includes various physiological signals such as heart rate, respiration rate, body temperature, limb movement, blood oxygen levels, eye movement, and hours of sleep.



## Model Development



### Data Preprocessing and Exploration



- **Standardization:** Standardized naming conventions for clarity.

- **Handling Missing Values:** Ensured the dataset was complete with no missing values.

- **Data Balancing:** Achieved an even representation across different stress levels, with 126 instances per category.



### Model Training



We implemented several machine learning algorithms, including:



- **Logistic Regression**

- **Random Forest Classifier**

- **Gradient Boosting Classifier**

- **Stochastic Gradient Descent Classifier**



Each model was evaluated using 5-fold cross-validation to ensure robust performance.



### Model Evaluation



The models were assessed on a test dataset using metrics such as accuracy, F1 score, precision, and recall. Key findings include:



- **Logistic Regression:** Perfect accuracy (1.0000) across all metrics.

- **Random Forest Classifier:** Accuracy of 0.9841.

- **Gradient Boosting Classifier:** Accuracy of 0.9762.

- **Stochastic Gradient Descent Classifier:** Accuracy of 0.9524.



Logistic Regression emerged as the most effective model for predicting stress levels based on physiological data.







## Conclusion



Our project successfully demonstrated the potential of machine learning in objectively detecting stress levels through physiological data analysis. The insights gained can empower individuals to manage stress proactively and make informed health decisions. Future work may explore further feature engineering and model optimization to enhance predictive accuracy and real-world applicability.
