# Prosper Loan Data Exploration

An analysis of loan data from the peer-to-peer lending company [Prosper](https://www.prosper.com)

## Files in Repo:

1. [The analysis notebook](prosper-data-analysis.ipynb).
2. [Summary of key insights](prosper-data-analysis-presentation.ipynb)
3. [Cleaned dataset](prosper_clean.csv)

## Table of Contents
- [Background](#background)
- [Dataset](#dataset)
- [Packages](#packages)
- [Summary of Process](#summary-of-process)
- [Key Insights](#key-insights)

## Background
##### This project was part of the projects in Udacity's Data Analyst Nano Degree

Loans are true lifesavers. They help us handle emergencies and pursue important personal projects. But the potential for good isn't the only thing that loans carry. For investors, they also bring the risk of losing it all. Prosper is a company that believes in the potential of loans to do good. It provides individuals a platform to borrow or lend money. The platform has had both good and bad loans. In this project, I investigate the factors that affect the risk level of Prosper loans, and perhaps offer some insight to investors.

## Dataset
+ [Prosper Dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) - csv
+ [Variable Definitions](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit) - Google Sheet 

The dataset has 113937 loan entries with 81 observations per entry.

## Packages
The analysis was done in Jupyter Notebook. The packages used were:  
| | |
|--- |---|
| Pandas | Numpy 
|Seaborn |Matplotlib pyplot|

## Summary of Process
1. Gathering - from url
2. Cleaning - selecting only a few columns for indepth analysis and tidying up the data
3. Analyzing - deriving insights
4. Visualizing - making descriptive plots

## Key Insights
+ The most common loan term  is **Three Years**
+ The most common loan amount is in the \$1000-4999 range
+ Loan completion rate increases as income range increases.
+ 1-year loans have the highest completion rate at about 95%
+ Most Prosper lendees are in the \$25k-49.9k income bracket.
+ Most Prosper loan clients had no prior delinquencies. 
+ 64\% of the lendees with prior delinquencies fully paid off their Prosper loans.
+ Home ownership does not affect loan repayment/completion
