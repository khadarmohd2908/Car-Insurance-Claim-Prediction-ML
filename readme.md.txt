readme.md
# 🚗 Car Insurance Claim Prediction Using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to predict whether a customer is likely to make a car insurance claim based on customer, vehicle, and insurance policy information.

The project follows a complete Machine Learning workflow, including data cleaning, exploratory data analysis, feature engineering, model building, model evaluation, and hyperparameter tuning.

## 🎯 Objective

The objective of this project is to build a classification model that predicts whether a customer is likely to make an insurance claim.

* **0 → No Insurance Claim**
* **1 → Insurance Claim**

## 📊 Dataset Features

The dataset contains the following features:

* Age
* Gender
* Driving License
* Region Code
* Previously Insured
* Vehicle Age
* Vehicle Damage
* Annual Premium
* Policy Sales Channel
* Vintage
* Response (Target Variable)

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

## 🔄 Project Workflow

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Train-Test Split
7. Model Building
8. Model Evaluation
9. Hyperparameter Tuning using RandomizedSearchCV
10. Model Comparison
11. Final Prediction

## 🤖 Machine Learning Models

The following classification models were used:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

Random Forest was further optimized using **RandomizedSearchCV**.

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

## 📂 Project Structure

```text
Car_Insurance_Claim_Prediction/
│
├── car_insurance_claim_prediction_1000.csv
├── Car_Insurance_Claim_Prediction.ipynb
├── README.md
└── requirements.txt
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <repository-url>
```

### 2. Install required libraries

```bash
pip install -r requirements.txt
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the project notebook

```text
Car_Insurance_Claim_Prediction.ipynb
```

Run all cells to reproduce the analysis and model results.

## 📌 Conclusion

This project demonstrates an end-to-end Machine Learning classification workflow for predicting car insurance claims.

Multiple machine learning models were trained and compared using different evaluation metrics. RandomizedSearchCV was used to tune the Random Forest model and identify better hyperparameters.

The final model can help insurance companies identify customers with a higher likelihood of making an insurance claim and support data-driven decision-making.
