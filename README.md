🌳 Loan Repayment Prediction using Random Forest

LendingClub Data (2007–2010)

🔍 Project Overview

This project analyzes publicly available LendingClub loan data to build a machine learning classification model that predicts whether a borrower is likely to fully repay a loan.

LendingClub connects borrowers with investors. From an investor’s perspective, accurately identifying borrowers with a high probability of repayment is critical for minimizing risk and maximizing returns.

The dataset used spans 2007–2010, a period before LendingClub went public, and provides valuable insight into borrower behavior.

🎯 Business Problem

As an investor, the key question is:

Will this borrower pay back the loan in full?

The objective of this project is to:

Analyze borrower financial and credit attributes

Build a Random Forest classification model

Predict loan repayment outcomes

Support risk-aware investment decisions

📂 Dataset Description

Source: LendingClub (public dataset)

Time Period: 2007–2010

Format: CSV (cleaned, no missing values)

🎯 Target Variable

Not.Fully.Paid

0 → Loan fully paid

1 → Loan not fully paid

🔑 Example Features

Credit policy status

Interest rate

Loan purpose

Annual income

Debt-to-income ratio

FICO credit score

Revolving balance

Number of credit inquiries

🧠 Approach & Methodology

1️⃣ Exploratory Data Analysis (EDA)

Loan purpose distribution

Credit score vs repayment behavior

Interest rate analysis

Risk segmentation

2️⃣ Data Preprocessing

Feature selection

Encoding categorical variables

Train-test split

Handling class imbalance (if applicable)

3️⃣ Model Building

Random Forest Classifier (Scikit-learn)

Hyperparameter tuning

Feature importance analysis

4️⃣ Model Evaluation

Confusion Matrix

Accuracy

Precision, Recall

F1-Score

🛠️ Tools & Technologies

Languages & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Core Concepts

Classification Modeling

Random Forest Algorithm

Feature Importance

Credit Risk Analysis

Model Evaluation Metrics

📈 Key Insights

Borrowers with lower FICO scores and higher interest rates are more likely to default

Loan purpose plays a significant role in repayment behavior

Random Forest captures non-linear relationships better than simple linear models

✅ Results

✔ Built a robust Random Forest classifier

✔ Identified key features influencing loan default

✔ Demonstrated a practical credit risk modeling use case
