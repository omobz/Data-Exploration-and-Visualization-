# Data-Exploration-and-Visualization
**Prosper Loan Data**
## Dataset 
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Data dictionary to understand the variables more can be found with this link: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

### Data Assessing and Cleaning

- There were too many columns in the original dataset and not all were needed for this analysis so some columns were selected and used to create a subset of the original dataset.
- Duplicates were dropped
- Null values in the borrower apr was dropped as there were only 25 and considering the size of our dataset it can be dropped without resulting in a bias in the final analysis.
- Appropriate Data types were assigned to the variables
- listing category numeric was changed to string.

## Summary of the findings
From this Analysis we can say that 

- The BorrowerAPR has a multimodal distribution with maximum peak between 0.34 and 0.36
- Most of the Borrowers in this data still have their loans running and are running for a duration of 36months.About 5000 loans have been defaulted.
- There is an almost equal percentage of Home owners ad non home owners amongst the borrowers. Although Home owners are more.
-  The loans taken in the year 2013 is rather high compared to other years in the distribution.And 2009 had the lowest number of people borrowing.
- People took loans for various reason but Debt Consolidation is the top most reason given for taking a loan.This discovery can lead to further investigation on the credit history and scores of borrowers if its an area of interest.
- Most of the loans are given for a period of 36 Months/3 Years.
- A large number of Borrowers are Employed and they make up the majority of the distribution.
- There was a significant sharp decline of Borrower APR from the Year 2011-2014 but its still seems like a random distribution as the relationship went from positive to negative over the same number of years.
- Even though there is an almost equal number of home owners and non home owners in our data, The number of non home owners that have completed their loan is more that home owners, Also more home owners still have their loans running.
-  Suprisingly there is no significant relationship between the borrower's APR and these variables: Loan year, Employment Status of the borrower, the Loan amount given to the borrower.
-  There is a negative correlation between the loan Amount and the Borrowers APR and the Duration of the the loan did not have an effect on it.
-  Borrowers who do not own a home tend to have a higher borrower's APR when compared to borrowers who owns a home.

## Key Insight
From the Subset chosen for this analysis: 

Only the Borrower owning a home showed a significant relationship when used on the relationship between the Borrowers APR and the Tenure . Hence not owning a home as a borrower will lead to an increase in your APR across the Terms. 
