# Paisabazaar Banking Fraud Analysis

The financial industry has witnessed a significant rise in fraudulent activities and credit risks over the past decade,
making fraud detection and credit risk assessment critical areas of focus for banks and financial institutions.
In this project, I analyze a large-scale dataset provided by Paisabazaar, which includes customer demographics, 
financial details, credit utilization patterns, and payment behaviors. By conducting Exploratory Data Analysis (EDA) and visualizations,
the goal is to uncover key insights that can help detect fraudulent behavior, assess financial risk, and strengthen customer credit profiling.

The dataset consists of 81782 records with 28 attributes related to customer identity, 
financial history, and credit score. Key columns include Annual Income, Monthly Inhand Salary, 
Number of Bank Accounts, Number of Credit Cards, Interest Rate, Outstanding Debt, Credit Utilization Ratio, 
Credit History Age, Payment Behavior, and Credit Score. 
These variables are essential indicators of financial health and are widely used in risk modeling and fraud detection systems. 
The presence of demographic details such as Age, Occupation, and SSN adds an additional layer for identifying potential fraud cases,
such as multiple accounts linked to the same identity or unrealistic financial behaviors.

The first step of the project involves data cleaning and preprocessing. 
Although the dataset does not contain missing values, duplicate entries or repeated customer records across multiple months are also examined to ensure data integrity.

The next stage focuses on Exploratory Data Analysis (EDA).
Here, I investigate how different features relate to fraudulent or risky financial behavior.
For instance, the relationship between Credit Utilization Ratio 
and Credit Score can reveal whether customers who use higher proportions of their available credit are more likely to have poor scores.
Similarly, analysis of Number of Delayed Payments and Delay from Due Date can highlight patterns of financial irresponsibility, 
which are often precursors to fraud or default. Visualizations such as histograms, boxplots, heatmaps,
and correlation matrices help identify trends, anomalies, and feature interdependencies.

One of the core aspects of this project is fraud analysis. 
Fraudulent behavior often manifests in unrealistic or contradictory patterns in financial data. 
For example, a customer with a low annual income but multiple credit cards, high loan counts, 
and excessive monthly spending could indicate suspicious activity. Similarly, sudden changes in Credit Limit, 
unusually high Credit Inquiries, or inconsistent Payment Behavior can serve as red flags.
By combining statistical analysis and visual exploration, we aim to highlight such irregularities.

Another key outcome of this project is credit risk profiling.
The dataset contains a labeled feature, Credit Score, categorized as Good, Standard, or Poor.
By analyzing the distribution of features across these groups, I can uncover the primary factors contributing to poor credit performance. 
For example, high EMI obligations compared to income, frequent delays in payment, and poor credit mix are expected to correlate strongly with lower credit scores. 
These insights are valuable for banks in developing scoring models and improving lending decisions.

Visual storytelling plays a vital role in this analysis. 
Through bar charts, scatter plots, and trend graphs, 
I illustrate how financial indicators differ across customer segments.
Heatmaps and pair plots help identify multi-feature interactions, 
while boxplots highlight outliers that may correspond to fraud. 
For instance, we can visualize the variation of Outstanding Debt across different income groups 
or compare Payment Behavior with Credit Utilization Ratios to detect unusual spending habits.

In conclusion, this project provides a comprehensive understanding of customer financial behavior using real-world banking data. 
By leveraging EDA and visualization techniques, I identify patterns of fraud, risk factors affecting credit scores, and relationships between financial attributes. 
The insights gained not only aid in detecting fraudulent activities but also enable financial institutions to optimize their credit risk strategies and enhance customer profiling systems. 
Ultimately, this project demonstrates how data-driven analysis can contribute to safer, more transparent, and more efficient banking systems.


## What do I suggest the client to achieve Business Objective ?

To address the business objective of reducing fraud risk and improving credit portfolio quality, I recommend a data-
driven approach using the insights derived from the analysis. First, customers can be segmented based on their credit
score, debt levels, and utilization ratios to identify high-risk groups. Customers showing consistently high outstanding
debt, EMI burden, and credit utilization should be flagged for closer monitoring. The institution should encourage
timely payments by offering reminders, flexible repayment plans, and financial counseling. At the same time, predictive
models can be developed to identify early warning signals of potential fraud or default. By promoting responsible
borrowing and proactive engagement, the bank can improve repayment rates. Automated alerts and stricter loan
eligibility criteria for high-risk customers will further reduce exposure. Meanwhile, low-risk customers should be
rewarded with better credit terms to strengthen loyalty. Over time, these actions will not only reduce fraud but also
improve the overall profitability and customer trust of the organization.
