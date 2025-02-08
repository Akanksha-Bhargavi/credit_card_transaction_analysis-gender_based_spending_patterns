# **Credit Card Transaction Analysis: Gender-Based Spending Patterns**

## **Overview**
- This project focuses on analyzing credit card transaction data to uncover spending patterns and differences between genders. It explores transaction amounts, spending categories, and investigates how gender influences purchasing behavior. The dataset contains transactions from both men and women, over multiple categories such as travel, electronics, clothing, and more.

## **Objectives**
- Understand spending patterns: Analyze transaction amounts and categorize them based on various expense types.
- Compare spending between genders: Investigate if there are significant differences in spending behavior between men and women.
- Categorize spending by type: Identify how much is spent in each category and what percentages are allocated to each expense type.
  
## **Data Source**
- The dataset used for this analysis is sourced from the Comprehensive Credit Card Transactions Dataset on Kaggle.

## **Installation**
- Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/credit-card-spending-analysis.git
cd credit-card-spending-analysis
```
- Install the necessary libraries in R:
```bash
install.packages(c("dplyr", "stringr", "ggplot2", "lubridate", "BSDA", "DescTools", "EnvStats", "tidyr", "knitr"))
```

## **Data Exploration & Preprocessing**
- Before analyzing the data, the following preprocessing steps were performed:
- Converted the Birthdate column to a date format and calculated customer age.
- Handled missing data and performed basic exploratory analysis (e.g., summary statistics and structure inspection).

## **Analysis & Visualization**
- The project explores various aspects of the data, including:
- Transaction Amount Distribution: Distribution of credit card transaction amounts.
- Total Transaction Amount by Category: Bar plot showing the total transaction amounts across categories like travel, electronics, etc.
- Spending Differences by Gender: Pie chart and bar chart comparing spending between genders.
- Spending Categories by Gender: A breakdown of total spending amounts by category for each gender.
- Chi-Square Test: Statistical test to check if there is an association between gender and spending category.
- T-Test: Statistical test to check if there is a significant difference in mean transaction amounts between genders.
- The visualizations and statistical tests help uncover key insights into consumer spending behavior.

## **Findings**
- Transaction Amount Distribution: Most transactions are small, with occasional high-value transactions, especially in travel and electronics.
- Gender-Based Spending: Women account for a significantly larger portion of the spending (86.7%) compared to men (13.3%).
- Spending Categories: Travel and electronics are the dominant categories, comprising a substantial portion of the total spending.
- Statistical Analysis: The Chi-Square test did not reveal a significant association between gender and spending category. Similarly, the t-test showed no significant difference in mean transaction amounts between men and women.
  
## **Conclusion**
- This analysis provides valuable insights into how gender influences spending patterns, showing that women tend to spend more on credit cards, although the statistical tests did not find significant differences in spending amounts. Travel and electronics were the most significant categories in terms of spending.

## **References**
- Comprehensive Credit Card Transactions Dataset-Kaggle(https://www.kaggle.com/datasets/rajatsurana979/ comprehensive-credit-card-transactions-dataset)
