# (Loan Data from Prosper)
## by (Adewale Yusuff Adeleke)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
         Data tidiness are done, as there are few variables with unmatched dtypes, and Year was extracted from 'ListingCreationDate' and 'ClosedDate'so as to be able to effectively run numetrical functions. Some rows where dropped as a result of incomplete data and null values.


## Summary of Findings

>  On the course of this project, few data tidiness are done, as there are few variables with unmatched dtypes, and Year was extracted from 'ListingCreationDate' and 'ClosedDate'so as to be able to effectively run numetrical functions. Some rows where dropped as a result of incomplete data and null values.
     My major area of interest is on repayment of loan (Loanstatus), so as to know what factors contributed to effective loan repayment.
     The analysis shows that increase in StatedMonthlyIncome and decrease in BorrowerRate tends to have positive effects on  LoanStatus. Also people that are employed and more importantly when their employment status is verifiable tends to complete their loan payments compared to the unemployed or retired conterparts.
      As it was deduced from my bivariate explorations above that high interest rate and not owning a house have adverse effects on loan payments, the above multivariate explorattion further affirmed the assertions. The chart in the middle (Completed) shows that borrowers tends to complete their payment more when they own house, as compared to when they do not, and the interest rate is relatively low compared to the two other charts.
         Even when the loan amont is high, borrowers tends to complete their loan payments, especially when they have better reccommendations.
         I observed that there is a partial negative correlation between the LoanOriginalAmount and the BorrowerRate. As the amount borrowed is increasing, the interest rate tends to go down.


## Key Insights for Presentation

For the presentation, my focus is on the cummulative effect of interest rate and owning a house on the loan payment. The categorical variables  IsBorrowerHomeowner and LoanStatus  are plotted on Facetting box against BorrowerRate on y axis. figsize of 4 where used for clarity sake.
            The chart in the middle (Completed) shows that borrowers tends to complete their payment more when they own house, as compared to when they do not, and the interest rate is relatively low compared to the two other charts.