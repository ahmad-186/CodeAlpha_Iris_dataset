# 🌸 Iris Flower Classification using Random Forest

This project involves building a machine learning model to classify Iris flower species using the Random Forest Classifier. It uses one of the most famous datasets in the machine learning community — the **Iris dataset**.

---

## Project Overview

- **Objective**: Predict the species of Iris flowers (Setosa, Versicolor, Virginica) based on features like petal and sepal dimensions.
- **Model Used**: Random Forest Classifier
- **Evaluation Techniques**:
  - Train-Test Split
  - Cross Validation
  - Grid Search CV
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## 📊 Dataset Description

The Iris dataset consists of 150 rows with 5 columns:

| Feature         | Description              |
|----------------|--------------------------|
| Sepal Length   | Length of the sepal (cm) |
| Sepal Width    | Width of the sepal (cm)  |
| Petal Length   | Length of the petal (cm) |
| Petal Width    | Width of the petal (cm)  |
| Species        | Target class             |

---

## Techniques Used

### 1. Random Forest Classifier
A robust and accurate ensemble method used for classification tasks.

### 2. Cross Validation
Used to evaluate model performance more reliably by splitting the dataset into multiple folds.

### 3. GridSearchCV
Hyperparameter tuning using exhaustive search over a parameter grid.

### 4. Accuracy Score
Evaluates the overall correctness of the model.

### 5. Confusion Matrix
Displays the number of correct and incorrect predictions by class.

### 6. Classification Report
Shows precision, recall, f1-score, and support for each class.

## Results
  - Best Cross-Validation Accuracy: ~95.5%
  - Best GridSearchCV Score: ~98%
  - Final Accuracy Score: 100%

While 100% accuracy suggests excellent performance, it is likely because the Iris dataset is small, balanced, and clean — not necessarily because the model is perfect.

## Overfitting Consideration
To avoid overfitting:

  - Applied Cross-Validation
  - Tuned hyperparameters using GridSearchCV
  - Used ensemble model (Random Forest) with controlled depth and estimators
