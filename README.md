# 🏦 Loan Approval Prediction with Interactive EDA

This repository contains a Machine Learning project that predicts loan eligibility using a **Random Forest Classifier**. It features an interactive Exploratory Data Analysis (EDA) dashboard built with **Plotly**.

## 📊 Interactive Features
Unlike static plots, this project uses Plotly to provide:
- **Loan Status Distribution:** A pie chart showing the ratio of approvals vs. rejections.
- **Demographic Analysis:** Bar charts exploring Gender and other categorical factors.

## 🛠️ Data Preprocessing
- **Missing Value Imputation:** Categorical values are filled with `mode`, and numerical values (LoanAmount) are handled with `median` to remain robust against outliers.
- **Feature Engineering:** Dropped irrelevant identifiers (Loan_ID) to focus on predictive power.

## 🚀 Installation & Usage
1. Clone this repo: `git clone https://github.com/YOUR_USERNAME/Loan-Approval-Prediction.git`
2. Install requirements: `pip install -r requirements.txt`
3. Open `loan_prediction.ipynb` in VS Code or Jupyter.

## 📉 Results
The model uses financial and demographic data to automate the decision-making process for financial institutions.