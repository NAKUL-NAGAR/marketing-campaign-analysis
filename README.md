# Marketing Campaign Analysis

## Project Overview

This project performs exploratory data analysis (EDA) on a Marketing Campaign dataset using Python.

The analysis focuses on customer information, income, education, purchasing behavior, campaign responses, and spending patterns.

## Dataset

The dataset contains customer-related information such as:

- Customer ID
- Year of Birth
- Education
- Marital Status
- Income
- Number of children and teenagers
- Customer enrollment date
- Recency
- Product spending
- Web, catalog, and store purchases
- Campaign responses
- Complaints

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL
- Jupyter Notebook

## Data Analysis Performed

### Data Loading
- Loaded the Excel dataset using Pandas.
- Inspected the first rows and complete dataset.

### Data Cleaning
- Checked for missing values.
- Filled missing Income values using the mean.
- Checked data types.
- Converted `Dt_Customer` to datetime format.
- Checked for duplicate rows.

### Feature Engineering

Created new columns:

- `Total Spend`
- `Total Purchases`
- `ROI`
- `Total_Children`
- `Income_Per_Child`

### Categorical Data

Performed one-hot encoding for:

- `Education`
- `Marital_Status`

### Campaign Analysis

Analyzed campaign acceptance using:

- `AcceptedCmp1`
- `AcceptedCmp2`
- `AcceptedCmp3`
- `AcceptedCmp4`
- `AcceptedCmp5`
- `Response`

### Data Visualization

Created visualizations using Matplotlib and Seaborn:

- Campaign acceptance bar chart
- Education count plot
- Pair plot for Income, Wine Spending, and Meat Product Spending
- Education distribution pie chart

## Key Visualizations

The project includes analysis of:

- Customer income distribution
- Product spending patterns
- Relationship between income and spending
- Campaign acceptance
- Education distribution
- Customer purchasing behavior

## Files

- `test.ipynb` — Jupyter Notebook containing the analysis
- `marketing_campaign.py` — Python code file
- `marketing_campaign.xlsx` — Excel dataset

## How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
