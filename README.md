# Telecom Churn Prediction

## Project Overview
The telecom industry experiences a significant churn rate of 15-25% annually. Retaining high-value customers is crucial for profitability as it is 5-10 times costlier to acquire new customers than to retain existing ones. 

This project aims to build a machine learning model to predict customer churn based on their usage patterns, behavior, and payment history, enabling telecom companies to take proactive steps to reduce churn.

---

## Problem Statement
In a competitive telecom market, identifying high-risk customers for churn is vital. This project focuses on predicting the likelihood of customer churn using advanced machine learning techniques and a dataset with over 170 features.

---

## Dataset Description
- **Training Data (`train.csv`)**:
  - Contains 172 columns with the target variable `churn_probability` (0 or 1).
  - Primary key: `id`.

- **Test Data (`test.csv`)**:
  - Contains 171 columns without the target variable.
  - Predictions will be made on this data.

- **Sample Submission (`sample.csv`)**:
  - Format for submission: `id, churn_probability`.

- **Data Dictionary (`data_dictionary.csv`)**:
  - Contains definitions for all acronyms and variables.

---

## Features
- **Demographics**: Age on Network (AON), Circle ID.
- **Call Behavior**: Local, STD, ISD, Incoming, and Outgoing call statistics.
- **Data Usage**: Internet usage (2G, 3G), volume, and recharge patterns.
- **Revenue Metrics**: Average revenue per user (ARPU), recharge amounts.

---

## Methodology
1. **Exploratory Data Analysis (EDA)**:
   - Analyzed patterns, correlations, and trends in customer data.
   - Identified key features affecting churn.

2. **Data Preprocessing**:
   - Handled missing values.
   - Encoded categorical variables.
   - Scaled numeric features for model readiness.

3. **Model Building**:
   - Implemented various machine learning algorithms:
     - Logistic Regression
     - Decision Trees
     - Random Forest
   - Evaluated models based on classification accuracy.

4. **Prediction**:
   - Applied the trained model to the test dataset.
   - Prepared submission file in the required format.

---

## Results
- Achieved **X% Classification Accuracy** on the validation dataset.
- Identified key features contributing to customer churn.
- Built a scalable solution to predict churn effectively.

---

## Tools and Libraries
- Python (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Kaggle for dataset hosting and evaluation

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-url.git
