# EDA_Diabetes_Prediction

# Pima Indians Diabetes Classifier 🩺

Predict whether a patient is diabetic based on diagnostic measurements using Machine Learning.

## 🔍 Project Overview

This project uses the **Pima Indians Diabetes Dataset** to build a classification model that predicts the onset of diabetes in female patients. The dataset contains several medical predictor variables (such as glucose levels, BMI, insulin levels) and one target variable: whether the person has diabetes.

The model is built and evaluated using **Scikit-learn** with a focus on performance and interpretability.

## 📊 Dataset

- **Source:** [Pima Indians Diabetes Database - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Records:** 768
- **Features:** 8 medical features + 1 output variable (`Outcome`)
- **Target:** `Outcome` — 1 (diabetic), 0 (non-diabetic)

## 🧠 Models Used

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- Model performance compared using metrics like **accuracy**, **precision**, **recall**, and **F1 score**.

## 📈 Performance

| Model              | Accuracy | F1 Score |
|-------------------|----------|----------|
| Logistic Regression | 77%      | 0.76     |
| SVM (RBF Kernel)   | 79%      | 0.78     |
| Random Forest      | 81%      | 0.80     |
| KNN                | 76%      | 0.75     |

📌 The final model was selected based on highest F1 score and accuracy balance.


## 📌 Key Concepts Covered

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Scaling
- Model Training & Testing
- Performance Evaluation (Accuracy, F1 Score, Confusion Matrix)
- Cross Validation

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Pima-Diabetes-Predictor.git
   cd Pima-Diabetes-Predictor
pip install -r requirements.txt

jupyter notebook main.ipynb


## 📂 Project Structure

