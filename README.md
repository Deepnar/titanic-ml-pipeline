# Titanic Survival Prediction — End-to-End ML Pipeline

This project builds a complete **machine learning pipeline** on the Titanic dataset,
covering data cleaning, feature engineering, model training, and evaluation.

The focus is on understanding how raw, real-world data is transformed into a form suitable for machine learning models.

## Workflow Overview
1. Data inspection and missing value analysis
2. Data cleaning and preprocessing
3. Feature engineering
4. Model training using multiple algorithms
5. Model evaluation and comparison

## Data Cleaning
Key preprocessing steps include:
- Dropping high-missing-value columns (Cabin)
- Filling missing numerical values using median (Age)
- Filling missing categorical values using mode (Embarked)

## Feature Engineering
New features were created to better represent underlying patterns:
- FamilySize = SibSp + Parch + 1
- IsAlone (binary indicator)
- FarePerPerson

These transformations improve model interpretability and performance.

## Models Used
- Logistic Regression
- Random Forest Classifier
- Naive Bayes
- Support Vector Machine (with GridSearchCV)

## Evaluation Metrics
- Accuracy
- F1 Score
- Confusion Matrix

Multiple models are compared to understand trade-offs between bias, variance, and generalization.

## Dimensionality Reduction
- PCA is applied for visualization and insight into class separability in lower dimensions.

## Key Takeaways
- Real-world datasets require significant preprocessing before modeling
- Feature engineering often matters more than model choice
- Evaluation metrics provide different perspectives on performance

## Purpose
This project demonstrates practical ML skills required for:
- Applied data science
- Machine learning engineering
- Transitioning from theory to real datasets
