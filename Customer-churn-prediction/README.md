# Customer Churn Prediction

## Project Overview

Customer churn prediction is a machine learning project that predicts whether a customer will leave a company or continue using its services.
Businesses use churn prediction to identify customers who are likely to stop using their service and take preventive actions.

This project uses a **Random Forest Classifier** to predict customer churn based on customer information such as contract type, tenure, monthly charges, and other features.

---

## Dataset

The dataset contains customer information and whether they have churned or not.

Example dataset file:

data/churn.csv

Typical dataset columns may include:

* CustomerID
* Gender
* Tenure
* MonthlyCharges
* Contract
* PaymentMethod
* Churn

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Matplotlib
* Seaborn

---

## Project Structure

customer-churn-prediction
│
├── src
│   └── churn_prediction.py
│
├── notebook
│   └── churn_prediction.ipynb
│
├── data
│   └── churn.csv
│
└── README.md

---

## Machine Learning Workflow

1. Data Loading
2. Data Exploration (EDA)
3. Data Preprocessing
4. Train-Test Split
5. Model Training (Random Forest Classifier)
6. Prediction
7. Model Evaluation

---

## How to Run the Project

1. Clone the repository

git clone https://github.com/yourusername/AI-ML-Portfolio.git

2. Install required libraries

pip install pandas numpy scikit-learn matplotlib seaborn

3. Run the Python script

python src/churn_prediction._
