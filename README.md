# Daily-Transaction
Objective:● Analyze daily financial transactions to identify trends, patterns, and insights.
          ● Generate a comprehensive report with visualizations.
          
## Technology Used
  Jupyter Notebook 
  
## Steps
Step 1: Import Libraries and Load Data

Step2:Data Cleaning
● Handle missing values.
● Correct data types.
● Remove duplicates.

Step3:Exploratory Data Analysis(EDA)
● Summary statistics.
● Distribution of transaction amounts.
● Transaction counts by category and type.

Step 4: Time Series Analysis
● Trend analysis.
● Monthly and daily trends

Step 5: Correlation Analysis
● Analyze the correlation between transaction categories and amounts.

Step 6: Generate Report
● Summarize findings and visualizations.

## Summary
The financial transactions dataset was analyzed to identify key trends and insights. The
data cleaning process involved handling missing values, correcting data types, and
removing duplicates. Exploratory Data Analysis (EDA) revealed the distribution of
transaction amounts, transaction counts by category and type, and significant patterns
over time. Time series analysis highlighted monthly and daily transaction trends.
Correlation analysis identified relationships between different transaction categories
Household expenses are routine-heavy and necessity-driven.
Spending behavior is highly skewed, with few transactions contributing a large portion of total expenditure.
Expense tracking at a daily level helps identify high-impact days.
Category-wise analysis highlights essential vs discretionary spending.
Monthly and daily trend analysis is useful for budget planning and cash flow management.

## 1. Executive Summary
The dataset represents a personal or small business financial record characterized by a high volume of small, frequent expenses and occasional, high-value income or maturity events. The financial activity remained relatively stable until mid-2017, after which it saw significant volatility and several large-scale transactions.

## 2. Transaction Volume and Types
Dominance of Expenses: The vast majority of transactions are classified as Expenses (over 1,600 counts), significantly outnumbering Income and Transfers-Out.
Top Spending Categories: * Food is the most frequent category (over 500 transactions).
Transportation, Household, and Subscriptions follow as the next most common categories.
Niche categories like "Self-development" or "Equity Mutual Funds" have the lowest frequency.

## 3. Spending Patterns and Distribution
Transaction Magnitude: Most transactions are very small (clustered near 0 on the distribution plot). However, the distribution has a "long tail," with rare transactions reaching up to 250,000.

Correlation Insights:
There is a notable positive correlation between Salary and categories like Investment and Interest, suggesting a structured habit of moving income into savings.
Health and Household also show a degree of correlation, potentially indicating periods of high "lifecycle" maintenance costs.

## 4. Temporal Trends (2015–2018)
Stability (2015 – Mid-2017): Monthly and daily spending remained relatively flat and predictable during this period.
The "Late 2017 Spike": There is a massive surge in transaction amounts starting in late 2017.
A significant peak in daily transactions occurred just before January 2018, exceeding 400,000 in a single day.
This drove the monthly total for that period to over 500,000, likely representing a major investment, property purchase, or maturity of a fixed deposit.
2018 Decline: Following the late 2017/early 2018 peak, transaction amounts trended downward, ending the data series at a near-zero activity level in late 2018.

## 5. Key Observations
Frequency vs. Value: While "Food" is what the user spends money on most often, the "Maturity Amount" and "Investment" categories likely drive the total volume of money moved, as seen in the correlation heatmaps.

Periodic Spikes: The daily transaction chart shows regular, smaller spikes (around 50,000–70,000), which likely correspond to monthly rent or recurring loan payments.

## Key Findings
● The distribution of transaction amounts showed a right-skewed pattern with most
transactions clustered around lower values.
● Sales and Purchases were the most common transaction categories.
● Credit transactions were more frequent than Debit transactions.
● Monthly transaction trends revealed seasonal patterns with peaks in certain
months.
● Correlation analysis indicated strong relationships between certain transaction
categories
