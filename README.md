# Communicating findings from the exploration of the prosper loan dataset

By

Olamide Olowoniyi

Dataset Overview

I chose to explore the proper loan data for last project. The Prosper loan dataset contains
113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or
interest rate), current loan status, borrower income, and so many others. The columns I was
interested in which I later put in a new data frame and named (loan_target) consisted of 18
variables. However, may target variable was the BorrowerAPR, I was mainly interested in
finding out what variables had the strongest correlation with it and as a result, what factors
were responsible for determining a loan’s annual percentage interest rate. These questions
formed the basis of both my explanatory and exploratory analysis.

Here is a link to the data:
https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBkYx3z0XDEtI/edit#gid=0

Summary of Findings

The exploration analysis showed a very strong negative correlation between the borrower’s
APR and the prosper score. The higher the credit scores, the lower the interest rates. The
same thing applied to the prosper scores, where the higher the prosper scores, the lower
the interest rates.

There was no correlation between the borrower’s income levels and their loan interest
rates, however a slight positive correlation was observed between the borrower’s income
levels and their monthly loan payments. The higher the income level, the higher the
monthly loan payments. It is then safe to assume that borrowers from prosper loans should
reasonably be able to pay back their loans based on this trend.
There was also a negative correlation between the borrower’s income levels and their debt
to income ratio, where borrowers with low income levels had hight debt to income ratio.
Overall, it was clear from the exploration that the borrowers with prosper score >=10 have
the best APRs-which are typically less than 10% (0.1). Also, the best APRs (Below 0.1) are
mostly borrowers with a Prosperscore above 10 and above 700. However, there are some
borrowers with credit scores below 700, that have great prosper scores, but these cases
very few.

I also saw that more borrowers with lower credit scores are opting for the 36 month loans.
This was also observed with the prosper score data, with more borrowers opting for the 36
term loans and these borrowers were observed to have lower prosper scores than the other
borrowers going for the 12 or 60 month term loans.
Presentation Key Insights
For the explanatory presentation, my analysis was focused on the three variables I identified
to have influence the loan’s interest rate. I introduced the Borrower APR which is the
variable on which I was most focused on.

I proceeded to show the other two variables that had the strongest relationship with it and
how I came to the conclusion that they influenced the loan’s interest rate.
To wrap it up, I showed a multivariate analysis of all three variables.
