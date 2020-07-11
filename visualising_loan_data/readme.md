# Prosper Loan Dataset Exploration 
## by Chloe Ng


## Dataset
> This is a dataset of loan data from Prosper til 2014. There are 113,937 rows in the dataset with 81 features. Most variables are numeric in nature, other common features include loan and borrower ratings, and percentage of interests and yield. There are no data cleaning performed even though there exists a large number of null values because of nature of the features. The main features are Credit Grades, ProsperRating, Loan Status, Investors, and Percent Funded. This is because I believe Credit Grades, ProsperRating are how a lender determine whether or not to lend to a person, or by how much they would lend out. Other features such as loan term, loan amount, and the potential yield the lender can obtain could also affect the loan result. Therefore I will focus on features representing these factors for the data exploration, and disregard features such as fees and loss of the lender.


## Summary of Findings

1. The majority of borrowers receive C and D grades credits. 

2. Prosper Rating is similar to credit grades - most borrowers receive grade C rating.

3. Most of the loans last for 3 years, with 87778 loans. The second is 5 years, with 24545 loans. Very few loans (1614) last for 1 year only.

4. Most of the loan are current loans. What's good is that many of them (around 40000) are completed loans. However, there are around 10000 loans charged off, and 5000 defaults.

5. As the number of cycle increase, the number of defaults decrease. This may implicate that if the borrower has been repaying the loan for a longer period of time, the chance of the loan going default decrease.

6. there are no strong relationship between the numeric variables explored. The strongly correlated ones are total payment billed and total loans - they have a positive relationship. 

7. As we expected, it appears that the borrowers with higher credit grade seem to be supported by more investors, those with lower credit grades have less investors. Similar phenomenon can be observed in the Prosper Rating system as well.

8. There are more data points with higher total principal billed for borrower with negative score change.

## Key Insights for Presentation

> Firstly, the presentation shows some distribution of variables (that are the credit grades, prosper rating, loan term) as a start. I polished the two bar charts of rating from data exploration into one single chart with grouped bars. 
> Secondly, the presentation shows the interesting relationships among 3 variables, namely Score Change, Total Prosper Payments Billed, and loan status.
> Finally, the lack of significant relationships are shown through a heatmap of correlation matrix between variables.
