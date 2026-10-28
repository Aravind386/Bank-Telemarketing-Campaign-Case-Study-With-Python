
# 🏦 Bank Telemarketing Campaign Analysis Using Python

### 📊 Customer Behaviour | Campaign Performance | Term Deposit Subscription Analysis

A data analytics project using Python to analyse customer demographics, financial information, and telemarketing campaign data to understand the factors associated with term deposit subscriptions.

---

## 📌 Project Overview

The Bank Telemarketing Campaign Analysis project explores customer and campaign-related data to identify patterns associated with term deposit subscriptions.

Using Python libraries for data cleaning, exploratory data analysis (EDA), and visualization, this project examines customer characteristics, financial indicators, contact methods, and campaign interactions.

The objective is to identify customer segments with higher subscription rates and provide data-driven recommendations for improving marketing campaign effectiveness.

## 🎯 Project Objectives

- Analyse customer demographics, including age, occupation, education, and marital status.
- Understand the relationship between salary, account balance, and term deposit subscriptions.
- Identify customer segments with higher subscription rates.
- Evaluate campaign performance based on contact methods and number of contacts.
- Examine previous campaign outcomes and call duration.
- Perform data cleaning and exploratory data analysis using Python.
- Develop actionable recommendations to support customer targeting and resource allocation.

## 📊 Dataset Overview

The project uses a synthetic bank telemarketing dataset.

| Dataset Information | Details |
|---|---|
| Original Records | 20,000 |
| Records After Cleaning | 19,961 |
| Original Columns | 19 |
| Duplicate Rows | 0 |
| Duplicate Customer IDs | 0 |
| Target Variable | `response` |
| Analysis Type | Exploratory Data Analysis |

### Important Dataset Columns

| Column | Description |
|---|---|
| `customerid` | Unique customer identifier |
| `age` | Customer age |
| `job` | Customer occupation |
| `education` | Education level |
| `marital` | Marital status |
| `balance` | Account balance |
| `salary` | Customer salary |
| `housing` | Housing loan status |
| `loan` | Personal loan status |
| `contact` | Contact communication method |
| `duration` | Call duration |
| `campaign` | Number of contacts during the current campaign |
| `pdays` | Days since a previous campaign contact |
| `previous` | Number of contacts before the current campaign |
| `poutcome` | Outcome of the previous campaign |
| `response` | Whether the customer subscribed to a term deposit |

## 🛠️ Tools & Technologies

- **Python** – Data analysis and programming
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab** – Development and execution environment

## 🧹 Data Cleaning & Preparation

The following data preparation steps were performed:

- Inspected dataset structure, column names, and data types.
- Checked for missing values and duplicate records.
- Verified that customer IDs were unique.
- Filled missing age values using the median.
- Filled missing education and month values using the mode.
- Removed records with missing target responses.
- Rechecked the dataset after cleaning.
- Created age groups for customer segmentation.

After cleaning, the dataset contained **19,961 records with no missing values**.

## 📈 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Customers Analysed | 19,961 |
| Customers Who Subscribed | 4,295 |
| Customers Who Did Not Subscribe | 15,666 |
| Term Deposit Subscription Rate | 21.52% |
| Non-Subscription Rate | 78.48% |
| Average Customer Age | 41.15 years |
| Average Account Balance | 572.37 |
| Average Salary | 55,004.60 |

*Note: Salary and balance are shown in the dataset's recorded units; the currency is not specified.*

## 🔍 Exploratory Data Analysis

### 1. Customer Demographic Analysis

- Analysed customer age distribution.
- Compared subscription rates across age groups.
- Examined occupations, education levels, and marital status.
- Identified customer segments with comparatively higher subscription rates.

### 2. Financial Analysis

- Analysed customer salary and account balance.
- Compared average and median balances between subscribers and non-subscribers.
- Examined subscription rates by housing loan, personal loan, and credit default status.

### 3. Campaign Performance Analysis

- Compared subscription rates across contact methods.
- Examined the number of contacts made during the campaign.
- Analysed previous campaign outcomes.
- Explored call duration and its potential relationship with subscription behaviour.

### 4. Data Visualization

- Term deposit subscription distribution.
- Customer age distribution.
- Customers by occupation.
- Subscription rate by age group.
- Subscription rate by occupation.
- Subscription rate by education and marital status.
- Subscription rate by contact method.
- Subscription rate by campaign contact frequency.

## 💡 Key Insights & Findings

### Customer Subscription Overview

- **21.52% subscription rate:** 4,295 out of 19,961 customers subscribed to a term deposit.
- **78.48% non-subscription rate:** Most customers in the dataset did not subscribe.

### Age Group Analysis

- Customers below 30 had a subscription rate of **22.63%**.
- Customers aged 30–40 had a subscription rate of **21.08%**.
- Customers aged 40–50 had a subscription rate of **21.32%**.
- Customers aged 50–60 had a subscription rate of **22.09%**.
- Customers aged 60 and above had a subscription rate of **20.28%**.

### Occupation Analysis

- Retired customers had the highest observed subscription rate at **29.98%**.
- Students followed with **27.50%**.
- Management professionals had a subscription rate of **23.35%**.
- Housemaids had the lowest observed subscription rate at **17.82%**.

### Education & Marital Status

- Customers with tertiary education had a subscription rate of **23.92%**.
- Single customers had a subscription rate of **24.16%**, compared with 20.54% for married customers and 19.85% for divorced customers.

### Financial Behaviour

- Subscribers had an average account balance of **1,736.42**, compared with **253.23** for non-subscribers.
- The median account balance was **805** for subscribers and **38** for non-subscribers.
- Average salary was similar for subscribers and non-subscribers.

### Contact & Campaign Analysis

- Subscription rates were broadly similar across the recorded contact methods.
- The observed subscription rate varied with campaign contact frequency, but results for contact counts with small customer groups should be interpreted cautiously.
- Previous campaign outcomes and call duration provide additional variables for further investigation.

*These are descriptive findings from the supplied dataset. They show associations, not proof that a particular characteristic causes a customer to subscribe. The dataset is synthetic, so results should not be treated as actual bank customer behaviour.*

## 📌 Business Recommendations

- Prioritize customer segments based on measured subscription rates, while monitoring the size of each segment.
- Use account balance and customer characteristics to develop hypotheses for further campaign testing.
- Evaluate campaign contact frequency to avoid unnecessary repeated calls.
- Compare campaign outcomes across contact methods and previous campaign results.
- Track subscription rates alongside the number of customers contacted to avoid relying on percentages alone.
- Validate proposed targeting strategies through controlled experiments before using them in real campaigns.

## 🚀 Project Workflow

1. Load the dataset into Google Colab.
2. Import the required Python libraries.
3. Inspect the dataset and understand its structure.
4. Check missing values, duplicate rows, and unique customer IDs.
5. Clean missing values and prepare the data.
6. Analyse the target variable and calculate subscription rates.
7. Perform demographic, financial, and campaign analysis.
8. Create visualizations using Matplotlib and Seaborn.
9. Interpret findings and develop business recommendations.

## 💼 Skills Demonstrated

- Python programming for data analysis
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Missing-value treatment
- Data aggregation and group-based analysis
- Customer segmentation
- Statistical summaries and percentage calculations
- Data visualization
- Business insight generation
- Analytical problem-solving

## 📚 Key Learnings

- Understanding how to prepare a dataset for analysis.
- Calculating subscription rates across different customer segments.
- Using Pandas `groupby()` for comparative analysis.
- Visualizing categorical and numerical data.
- Interpreting customer and campaign trends.
- Translating analytical findings into practical recommendations.

## 👨‍💻 Author

**Aravind K**  
Data Analyst | MIS Reporting | Power BI Developer

📍 Bengaluru, India

📧 Email: [aravindaat656@gmail.com](mailto:aravindaat656@gmail.com)

---

## ⭐ Project Summary

The Bank Telemarketing Campaign Analysis project demonstrates how Python can transform customer and campaign data into meaningful insights through data cleaning, exploratory analysis, segmentation, and visualization.

The project highlights practical data analytics skills and shows how descriptive insights can support better marketing decisions and future campaign optimization.
