# Loan Approval Prediction Using Artificial Neural Network (ANN)

## 1. Project Overview

This project focuses on predicting loan approval status using an Artificial Neural Network (ANN), a Deep Learning technique.

The model analyzes applicant information and financial characteristics to predict whether a loan application is likely to be approved or rejected.

The objective is to automate the loan approval prediction process and support data-driven decision-making in financial institutions.

## 2. Problem Statement

Financial institutions receive numerous loan applications from customers with different financial backgrounds and credit profiles.

Manually evaluating each application can be time-consuming. This project uses an Artificial Neural Network to learn patterns from historical loan application data and predict loan approval outcomes.

## 3. Objectives

- Perform Exploratory Data Analysis (EDA).
- Understand important factors influencing loan approval.
- Clean and preprocess the dataset.
- Handle missing values and categorical variables.
- Perform feature scaling.
- Build an Artificial Neural Network (ANN).
- Train and evaluate the Deep Learning model.
- Predict loan approval status for new applicants.

## 4. Dataset Description

The project uses a loan approval dataset containing applicant information and financial details.

**Common dataset features may include:**

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target Variable)

*Note: Adjust the feature list to match your actual dataset.*

## 5. Technologies and Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

## 6. Deep Learning Algorithm

### Artificial Neural Network (ANN)

An Artificial Neural Network is a Deep Learning model inspired by the structure of the human brain.

It consists of interconnected layers of neurons that learn patterns from input data.

**ANN Architecture:**

- Input Layer: Receives applicant information.
- Hidden Layers: Learn complex patterns and relationships.
- Output Layer: Predicts loan approval or rejection.

## 7. Project Workflow

1. Data Collection
2. Data Loading
3. Data Cleaning
4. Handling Missing Values
5. Exploratory Data Analysis (EDA)
6. Categorical Feature Encoding
7. Feature Scaling
8. Train-Test Split
9. ANN Model Architecture Development
10. Model Compilation
11. Model Training
12. Model Evaluation
13. Loan Approval Prediction

## 8. Model Evaluation

The ANN model can be evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Loss

These metrics help evaluate the model's ability to correctly classify loan applications.

## 9. Business Applications

- Automating initial loan application screening.
- Supporting financial institutions in loan assessment.
- Reducing manual evaluation efforts.
- Identifying patterns in historical loan applications.
- Supporting data-driven lending decisions.

The model should be used as a decision-support tool rather than the sole basis for approving or rejecting real loan applications.

## 10. Project Structure

```text
Loan-Approval-Prediction-Using-ANN/
│
├── README.md
├── requirements.txt
├── main.py
├── dataset.csv
└── images/
```

## 11. Installation and Execution

### Step 1: Clone the repository

```bash
git clone https://github.com/naik-aarya/Loan-Approval-Prediction-Using-ANN.git
```

### Step 2: Navigate to the project directory

```bash
cd Loan-Approval-Prediction-Using-ANN
```

### Step 3: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Python file

```bash
python main.py
```

## 12. Conclusion

This project demonstrates how Artificial Neural Networks can be applied to loan approval prediction using applicant and financial information.

By learning patterns from historical loan application data, the ANN model can classify applications and provide useful insights to support financial decision-making.

---

**Author:** Aarya Naik

**GitHub:** https://github.com/naik-aarya
