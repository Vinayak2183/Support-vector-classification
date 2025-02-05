# Support Vector Machine (SVM) Classification

This repository demonstrates the use of a **Support Vector Machine (SVM)** for classification. The dataset used for this project is `Social_Network_Ads.csv`, which contains information about users and whether they purchased a product or not. The goal is to build an SVM model that can classify whether a user is likely to make a purchase based on the given features.

## Dataset Description

The dataset consists of the following columns:

- **User ID**: Unique identifier for each user (not used in training).
- **Age**: Age of the user.
- **EstimatedSalary**: Estimated salary of the user.
- **Purchased**: Target variable (1 = Purchased, 0 = Not Purchased).

## Process Workflow

### 1. Data Preprocessing
- The dataset is imported and examined for missing values.
- The feature variables (`Age`, `EstimatedSalary`) and the target variable (`Purchased`) are extracted.
- The dataset is split into **training** and **testing** sets to evaluate model performance.

### 2. Feature Scaling
- Since SVM is sensitive to feature scaling, **Standardization** is applied to the numerical features to bring them to a similar scale.

### 3. Training the SVM Model
- A **Linear SVM classifier** is trained on the preprocessed training data.

### 4. Model Evaluation
- Predictions are made on the test set.
- A **Confusion Matrix** is generated to evaluate model performance.
- **Accuracy** of the model is calculated.

### 5. Results Visualization
- The decision boundary of the trained SVM model is visualized.

## Conclusion

This project showcases how a **Linear SVM** can be applied to classify users based on their likelihood of purchasing a product. It also highlights the importance of **feature scaling** and **evaluation metrics** in assessing model performance.

## Dependencies

To run this project, the following Python libraries are required:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

