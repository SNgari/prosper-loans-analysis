
# Prosper Loan Data Exploration
## by Sylvia Ngari


## Dataset

The dataset used for this project is from the peer-to-peer lending company
[Prosper](https://www.prosper.com)  
The dataset is available in `csv` format while the variable definitions are 
in a `Google Sheet`
+ [Prosper Dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)
+ [Variable Definitions](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit)  

It consists of information on 113937 loans including loan status, loan terms 
and loan amounts.  
The huge dataset was trimmed down to 50066 rows to include only chargedoff 
and completed loans and only 10 of the 81 initial columns.

Two columns were added that grouped loan entries based on:
+ Past delinquencies
+ Loan amounts

The datatypes of a few columns were changed to `category` and `datetime` to 
better suit 
further exploration. The cleaned data was stored in a csv file `prosper_clean.csv` 
and will be used for the slideshow.

## Summary of Findings


In the exploration, I found that the most common loan term  is **Three Years**, 
and the most common loan amount is in the \$1000-4999 range. The number of 
loans in both categories far outdo those in other categories. Most of the Prosper 
loans were completed, but there was an observable increase in completion rate as 
incomes increased. The fewest number of loans had a 1-year term, but they also had 
the highest completion rate at about 95\%.

Most of the Prosper loans were taken by people in the \$25k-49.9k income bracket.
It was however interesting to note that the highest loan bracket offered (\$30k-35k)
was only taken by people with incomes of \$100k+. All the taken loans for the highest
loan bracket were fully paid off.

Most Prosper loan clients had no prior delinquencies. Among those with prior 
delinquencies, it was interesting to note that 64\% of them fully paid off their 
Prosper loans.

I discovered that home ownership is not a good determinant of whether a loan will 
be paid off or chargedoff. The numbers were almost similar for homeowners and 
non-home owners. The rates of prior delinquency follow the same trend.


## Key Insights for Presentation

For the presentation, I chose to focus on how loan completion is affected by
income, loan amounts, term, and previous delinquency. These four variables 
give a clear picture of what an investor may want to know when choosing to
fund a loan.

Higher income brackets have higher loan completion rates. When it comes to 
loan amounts, the lowest range (\$1k-4.9k) is the common pick across all 
income brackets. Most of the clients do not have prior delinquencies, but 
about 64\% of those with past delinquencies do pay off their Prosper loans.
The most common loan term is three-years, though the 1-year loans have the 
highest completion rate.