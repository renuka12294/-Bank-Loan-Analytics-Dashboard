# Bank Loan Analysis Dashboard

## 📊 Project Overview

This project focuses on analyzing a bank's loan portfolio and lending operations using Microsoft Power BI.

The dashboard provides an interactive view of loan applications, funded amounts, repayments, interest rates, Debt-to-Income (DTI) ratios, loan status, and other loan-related metrics.

The objective is to help understand loan portfolio performance, repayment behavior, and trends across different loan characteristics.

---

## 🎯 Problem Statement

The main objective of this project is to:

- Analyze loan portfolio performance and lending operations.
- Track Good Loans vs. Bad Loans and repayment behavior.
- Monitor important financial KPIs such as funded amount, repayments, interest rate, and DTI.
- Analyze trends across loan status, loan purpose, loan term, home ownership, and region.
- Build an interactive Power BI dashboard to provide useful portfolio insights.

---

## 📌 Key Performance Indicators (KPIs)

The dashboard tracks the following key metrics:

- **Total Loan Applications**
- **Total Funded Amount**
- **Total Amount Received**
- **Average Interest Rate**
- **Average Debt-to-Income (DTI) Ratio**

These KPIs provide an overview of the bank's lending activity and loan portfolio performance.

---

## 📈 Dashboard Pages

The project contains two main dashboard pages:

### 1. Summary Dashboard

The Summary page provides a high-level view of the bank's lending performance.

#### Key Visuals

- Good Loan Applications
- Bad Loan Applications
- Funded Amount vs. Amount Received by Loan Status
- Loan Applications by Loan Status
- Average Interest Rate by Loan Status
- Average DTI Ratio by Loan Status
- KPI cards for major portfolio metrics

---

### 2. Overview Dashboard

The Overview page provides a detailed analysis of different loan characteristics and trends.

#### Key Visuals

- Monthly Loan Applications
- Regional Analysis
- Loan Term Analysis
- Home Ownership Analysis
- Loan Purpose Breakdown

---

## 🔎 Interactive Features

The dashboard includes interactive features that allow users to explore the data dynamically.

### Filters

- **Loan Purpose**
- **Loan Grade**

### Navigation

- Page navigation buttons
- Reset Filters button

Users can apply filters and interact with the dashboard visuals to explore different aspects of the loan portfolio.

---

## 💡 Key Areas of Analysis

The dashboard focuses on several important areas:

### Loan Portfolio Performance

Analysis of loan applications, funded amounts, and amounts received to understand overall lending activity.

### Good vs. Bad Loans

Comparison of good and bad loan applications to understand loan portfolio quality.

### Repayment Behavior

Comparison of funded amounts and amounts received across different loan statuses.

### Interest Rate Analysis

Analysis of average interest rates across different loan statuses.

### DTI Analysis

Analysis of average Debt-to-Income ratios to understand borrower-related financial characteristics.

### Loan Trends

Analysis of monthly loan applications to identify changes in lending activity over time.

### Loan Segmentation

Loans are analyzed based on:

- Loan purpose
- Loan term
- Home ownership
- Region
- Loan status

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Excel**

---

## 📂 Project Structure

```text
Bank-Loan-Analytics-PowerBI/
│
├── README.md
├── Bank_Loan_Analytics.pbix
│
├── Dashboard/
│   ├── Summary.png
│   └── Overview.png
│
└── Dataset/
    └── bank_loan_data.csv
