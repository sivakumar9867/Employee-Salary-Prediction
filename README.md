# Employee Salary Prediction

A machine learning project that predicts whether an individual's annual income is above or below $50K based on demographic and employment-related attributes.

## 📌 Project Overview

This project uses the Adult Census Income dataset to build machine learning classification models for income classification.

The project includes data preprocessing, categorical feature encoding, feature scaling, train-test splitting, model training, and accuracy evaluation.

## 🎯 Objective

The main objective is to predict the income category of an individual based on features such as:

- Age
- Workclass
- Education
- Marital Status
- Occupation
- Relationship
- Race
- Gender
- Capital Gain
- Capital Loss
- Hours per Week
- Native Country

The target variable represents whether the individual's income is:

- `<=50K`
- `>50K`

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib

## 🔄 Project Workflow

1. Load the dataset
2. Explore the dataset
3. Handle missing/unknown categorical values
4. Encode categorical features using Label Encoding
5. Separate features and target variable
6. Apply Min-Max Scaling
7. Split the data into training and testing sets
8. Train machine learning classification models
9. Predict the test data
10. Evaluate model accuracy

## 🤖 Machine Learning Models

### 1. K-Nearest Neighbors (KNN)

Accuracy:

**86.17%**

### 2. Logistic Regression

Accuracy:

**81.91%**

### 3. Multi-Layer Perceptron (MLP)

Accuracy:

**86.17%**

## 📊 Results

| Model | Accuracy |
|---|---:|
| KNN | 86.17% |
| Logistic Regression | 81.91% |
| MLP | 86.17% |

KNN and MLP achieved the highest accuracy among the tested models, with an accuracy of 86.17%.


```markdown
## 📂 Project Files

```text
Employee-Salary-Prediction/
│
├── Employee_salary_Prediction.ipynb
├── adult.csv
├── requirements.txt
└── README.md

