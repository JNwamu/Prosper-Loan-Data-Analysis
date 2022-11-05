# (Prosper Loan Exploration)
## by (Jennifer Nwamu)

## Dataset

> The dataset used for this project is the Prosper Loan Dataset which consists of 113,937 loans with 81 features loans lent to borrowers from prosper system, including demographics of Loan borrowers, Loan original amount, Borrowers APR and other features.This dataset contains data from year 2006 to 2014. Each row in the dataset is identified by a listing key which respresents is unique to a loan. The dataset can be found in udacity [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) and data dictionary in this google document [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) . During wrangling some of the data and features not required for analysis was removed in order to make the dataset more understandable also a mis mappingof propser score with rating based on the data dictionary was perfomed along with correcting data type to categorical and date time respectively.

## Summary of Findings

> During exploration, I discovered that a strong negative relationship exists between a borrower's APR and their prosper score/ratings. The higher the ratings the lower the borrower APR and vice-versa. The factor that had a higher influence on the outcome of the loan was the amount borrowed and the interest rate of the loan. Those borrowers who took a high loan amount with a high APR usually didn't pay back on time and had past due loans. 
Besides the main variables of interest, most borrowers listed the reason for taking loans as debt consolidation with those who listec cosmetic procedure having a higher APR and a low loan amount. Loans where mostly taken by employed persons in California. The unemployed borrowers usually have a low prosper score/ratings.
Majority of Loans where approved within one month from their listing date.
There was a drop in loan activities between the end of 2008 which picked up by mid 2009.

## Key Insights for Presentation

> For the presentation, I would like to find out factors that affect the loan status and APR of borrowers based on various features of the loan such as demographics of borrowers, Loan amount, Ratings(Credit and Prosper), Propser scores and reason of taking the Loan. This would help the company to predict the future behavior of loan borrowers based on these set of features.  Hence, I would look at the distribution of the features of interest across the dataset and understand their relationship with other features through some charts, boxplot and heat map.
