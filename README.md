Thank you for the clarification. I'll update the README file to reflect the correct encoding of the values and the preprocessing steps taken. Here's the revised README file:

---

# README

## Project Overview

This project aims to build a predictive model using several machine learning algorithms to analyze clinical factors and predict certain outcomes. The methodology includes five pivotal stages and considers fifteen significant clinical factors.

## Clinical Factors

The following clinical factors were taken into consideration:

1. Age
2. Gender
3. Yellow Fingers
4. Smoking History
5. Peer Pressure
6. Anxiety
7. Fatigue
8. Allergies
9. Chronic Disease
10. Wheezing
11. Alcohol Consumption
12. Coughing
13. Difficulties in Swallowing
14. Shortness of Breath
15. Chest Pain

## Data Encoding

### Original Encoding

The original dataset had the following encoding:
- `Yes`: 2
- `No`: 1

### Label Encoding

To preprocess the data for machine learning algorithms, the following steps were taken:
- Gender was encoded as:
  - `Female (F)`: 0
  - `Male (M)`: 1

During the label encoding process, the `Yes/No` values for other variables were converted as follows:
- `Yes`: 1
- `No`: 0

## Cross-Validation

Cross-validation was performed using K-Fold to ensure the credibility of the model. Given the imbalanced nature of the dataset, conventional K-Fold cross-validation might introduce biases. To address this, Stratified K-Fold cross-validation was employed to maintain the class distribution across all folds.

## Algorithms Applied

The following machine learning algorithms were applied to the dataset:
1. Random Forest (RF)
2. K-Nearest Neighbors (KNN)
3. Logistic Regression
4. Support Vector Classifier (SVC)
5. Multinomial Naive Bayes

## Methodology Stages

The methodology includes the following five pivotal stages:

1. Data Collection: Gathering relevant clinical data for analysis.
2. Data Preprocessing: Encoding categorical variables, handling missing values, and scaling features if necessary.
3. Feature Selection: Identifying significant clinical factors to be included in the model.
4. Model Training: Applying various machine learning algorithms and tuning hyperparameters.
5. Model Evaluation: Assessing the performance of the models using appropriate metrics and cross-validation techniques.

## Conclusion

This README provides an overview of the project, the clinical factors considered, the data encoding process, cross-validation methodology, and the machine learning algorithms applied. This structured approach ensures the development of a reliable predictive model.

---
