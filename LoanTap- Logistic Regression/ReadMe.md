# Project Title  
**Creditworthiness Prediction and Underwriting for Personal Loans at LoanTap**

# Project Context

LoanTap is an online platform committed to delivering customized loan products tailored to millennials. By innovating within a traditionally dull loan sector, LoanTap offers instant, flexible loans with consumer-friendly terms, targeting salaried professionals and businessmen.

To enhance decision-making, the Data Science team at LoanTap is building an **automated underwriting layer** aimed at determining the creditworthiness of **MSMEs** (Micro, Small, and Medium Enterprises) as well as **individual borrowers**.

LoanTap currently offers four primary financial products:
- Personal Loan
- EMI Free Loan
- Personal Overdraft
- Advance Salary Loan

This project specifically focuses on the underwriting process for **Personal Loans**.

# Problem Statement

Given a set of attributes for an individual applicant, the objectives are:
- **Predict whether a personal loan should be approved or declined**.
- **Provide business recommendations on appropriate repayment terms** based on the applicant’s risk profile.

# Objectives

- Build a predictive model to assess applicant creditworthiness.
- Generate actionable insights to tailor repayment terms according to risk categories.
- Ensure fairness, transparency, and regulatory compliance within the underwriting process.

# Proposed Methodology

## Data Collection

- Historical data of personal loan applicants (approved and rejected).
- Key attributes may include:
  - Demographics (age, gender, education, location)
  - Employment information (type of employment, employer, salary, stability)
  - Financial health indicators (existing debts, assets, credit scores)
  - Loan-specific information (requested amount, tenure, purpose)
  - Behavioral patterns (bank statement analysis, spending patterns)

## Data Preprocessing

- Handle missing, inconsistent, or noisy data through imputation and normalization.
- Perform outlier detection and treatment.
- Feature encoding for categorical variables (e.g., employment type, loan purpose).

## Exploratory Data Analysis (EDA)

- Identify key variables influencing loan approval.
- Analyze relationships between attributes (e.g., salary vs. loan amount requested).
- Detect any biases or imbalance in the dataset (approved vs. rejected cases).

## Feature Engineering

- Create new features to create and train better model

## Model Development

- Experiment with classification models such as:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - XGBoost
- Evaluate models using metrics such as:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - AUC-ROC Curve
- Handle class imbalance using techniques like **SMOTE** or **Class Weights Adjustment**.

## Business Recommendation Engine

- Based on model outputs, recommend:
  - Loan amount limits
  - Interest rate tiers (based on risk profile)
  - Loan tenure suggestions
- Define clear rules or thresholds (e.g., "If debt-to-income ratio > 50%, recommend a lower loan amount").

# Impact

- Faster, more accurate loan decisions.
- Reduced default rates.
- Enhanced customer experience with personalized loan offers.
