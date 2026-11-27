
# Loan Approval Analysis Dashboard
### Credit Scoring & Risk Segmentation | Data Analytics Portfolio

## Project Overview

This project focuses on analyzing 50,000 loan applications to identify patterns and factors associated with loan approval decisions. The analysis explores customer demographics, financial conditions, credit history, loan characteristics, and geographic distribution.

An interactive dashboard was developed to monitor loan approval performance, evaluate customer risk profiles, and provide data-driven insights into lending patterns.

The dashboard allows users to filter data by province and loan product type, enabling more focused analysis of loan application trends and approval performance.

## Project Details

| Category | Description |
|----------|-------------|
| **Project Name** | Loan Approval Analysis Dashboard |
| **Dataset** | 50,000 loan application records with 21 variables covering customer demographics, employment status, financial conditions, credit history, loan products, and approval status across 12 provinces in Indonesia. |
| **Background** | Loan approval decisions require consideration of multiple customer characteristics, including credit scores, debt obligations, income levels, and credit history. This project was developed to explore how these factors relate to loan approval rates and customer risk profiles through an interactive dashboard. |
| **Objectives** | Analyze loan approval trends, identify customer risk segments, evaluate financial and credit-related factors, and compare approval performance across customer demographics, loan purposes, products, and provinces. |
| **Tools** | Microsoft Excel, Looker Studio |
| **Techniques** | Data Analysis, KPI Monitoring, Credit Scoring Analysis, Risk Segmentation, Descriptive Statistics, Data Visualization |
| **Dashboard** | [View Interactive Dashboard](https://datastudio.google.com/reporting/0ed1f11a-34f6-451e-9368-5495944dca2a) |

## Business Objectives

The main objectives of this project are:

1. Evaluate overall loan application and approval performance.
2. Identify credit score segments with different approval rates.
3. Analyze the relationship between Debt-to-Income Ratio (DTI) and loan approval.
4. Examine the impact of negative credit records and previous defaults.
5. Understand loan approval patterns across age groups and income levels.
6. Compare approval rates by loan purpose, product type, employment status, and province.
7. Present analytical findings through an interactive dashboard.

## Dataset Description

The dataset consists of **50,000 loan applications** and **21 variables**.

The dataset contains the following information:

| Category | Variables |
|----------|-----------|
| Customer Demographics | Age, Province |
| Employment Information | Employment Status, Employment Duration |
| Financial Information | Annual Income, Savings Assets, Current Debt |
| Credit Profile | Credit Score, Credit History Length, Previous Defaults, Recent Delinquencies, Negative Records |
| Loan Information | Loan Product Type, Loan Purpose, Loan Amount, Interest Rate |
| Financial Ratios | Debt-to-Income Ratio (DTI), Loan-to-Income Ratio (LTI), Payment-to-Income Ratio |
| Loan Status | Loan Approval Status |

**Dataset Dimensions:**
- Total Records: 50,000
- Total Variables: 21
- Geographic Coverage: 12 Provinces in Indonesia
- Loan Products: Credit Card, Revolving Credit, and Personal Loan

## Key Performance Indicators (KPIs)

The dashboard presents six main performance indicators:

| KPI | Result |
|-----|--------|
| Total Loan Applications | 50,000 |
| Approved Applications | 27,523 |
| Loan Approval Rate | 55.05% |
| Average Loan Amount | 33,041.87 |
| Average Credit Score | 643.61 |
| Average Interest Rate | 15.50% |

## Dashboard Features

The interactive dashboard consists of four main analytical sections:

### 1. Loan Approval Determinants
Analyzes the relationship between customer credit profiles and loan approval decisions.

- Credit Score Segmentation
- Debt-to-Income Ratio (DTI)
- Negative Credit Records

### 2. Customer Risk Profile
Examines customer financial conditions and credit risk characteristics.

- Customer Age Segmentation
- Annual Income Analysis
- Credit History and Default Records

### 3. Demographic & Interest Rate Analysis
Explores differences in loan approval performance across customer segments.

- Age Group Analysis
- Employment Status
- Interest Rate Distribution

### 4. Geographic Distribution & Key Insights
Compares loan approval performance across regions and summarizes the main analytical findings.

- Provincial Approval Rate Comparison
- Loan Product Analysis
- Automated Key Insights

**Interactive Features:**
- Province filter
- Loan product filter
- Dynamic KPI indicators
- Interactive charts
- Automatically updated analytical insights

## Key Findings & Business Insights

Based on the analysis of 50,000 loan applications, several important findings were identified:

### 1. Credit Score and Loan Approval

Credit score shows a strong positive pattern with loan approval rates.

- Customers with credit scores of 740+ have an approval rate of 88.4%.
- Customers with credit scores below 500 have an approval rate of only 10.6%.

### 2. Debt-to-Income Ratio (DTI)

Customers with higher debt obligations relative to their income tend to have lower loan approval rates.

- DTI below 20%: 64.6% approval rate.
- DTI of 50% or higher: 6.9% approval rate.

### 3. Credit History and Negative Records

Previous credit problems are associated with lower approval rates.

- Customers with recorded previous defaults (2,674 applications) have an approval rate of 0%.
- Customers with zero negative records have an approval rate of 59.2%.
- Customers with two negative records have an approval rate of 8.3%.

### 4. Age Group Analysis

Loan approval rates differ across age groups.

- Customers aged 55 and above: 79.6% approval rate.
- Customers aged 18–24: 30.2% approval rate.

### 5. Annual Income Analysis

Higher annual income segments show higher loan approval rates.

- Annual income above 100K: 73.1% approval rate.
- Annual income of 25K or below: 44.2% approval rate.

### 6. Geographic Analysis

Geographic differences in loan approval rates are relatively small.

- Highest approval rate: DKI Jakarta (56.9%).
- Lowest approval rate: Sumatera Selatan (53.5%).

## Analytical Conclusion

The analysis indicates that credit scores, debt-to-income ratios, previous default records, and negative credit history are important indicators associated with loan approval patterns.

Customers with stronger credit profiles, lower debt burdens, and fewer negative credit records generally demonstrate higher approval rates.

These findings can support customer risk segmentation, lending performance monitoring, and further credit risk analysis.

## Methodology

The project follows a structured analytical workflow:

1. **Data Understanding** – Examining the dataset structure, variables, and loan application characteristics.
2. **Data Preparation** – Reviewing data completeness and understanding variable definitions.
3. **Data Analysis** – Applying Excel formulas such as COUNTIFS, SUMIFS, AVERAGEIFS, and INDEX/MATCH to calculate analytical metrics.
4. **KPI Development** – Calculating total applications, approved applications, approval rates, average loan amounts, credit scores, and interest rates.
5. **Data Visualization** – Developing charts and interactive dashboard components to communicate analytical findings.
6. **Insight Generation** – Identifying patterns and comparing loan approval rates across different customer segments.

## Tools & Technical Skills

| Tool | Application |
|------|-------------|
| Microsoft Excel | Data analysis, calculations, KPI development, data validation, and dashboard preparation |
| Looker Studio | Interactive data visualization and dashboard presentation |

**Technical Skills Demonstrated:**
- Data Analysis
- Data Visualization
- Exploratory Data Analysis (EDA)
- KPI Development
- Credit Risk Analysis
- Customer Segmentation
- Financial Ratio Analysis
- Business Insight Generation
- Dashboard Development

## Data Quality & Limitations

- The dataset contains 50,000 records and 21 variables.
- The age variable contains 147 missing values.
- The employment status variable contains 153 missing values.
- Missing values were retained and excluded only from the corresponding age or employment analysis.
- The dataset does not specify a currency unit; therefore, monetary values are presented without a currency symbol.
- The `status_pinjaman` variable is interpreted as 1 = Approved and 0 = Rejected based on observed data patterns. This interpretation is an assumption because the original column does not contain an explicit label.
- The analysis is descriptive and identifies associations, not causal relationships.

## Project Deliverable

The main deliverable of this project is an interactive Loan Approval Analysis Dashboard designed to provide a comprehensive overview of loan application performance and customer risk segmentation.

**Dashboard Access:**

[Click Here to View the Interactive Loan Approval Dashboard](https://datastudio.google.com/reporting/0ed1f11a-34f6-451e-9368-5495944dca2a)

---

## Author

**Amanda Diyas Setiyoadi**

Data Analytics Portfolio

Interested in Data Analytics, Business Intelligence, Data Visualization, and Business Insights.
