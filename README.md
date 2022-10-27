# PROSPER LOAN DATA EXPLORATION
## by Winnie Minayo


## Dataset

The prosper loan dataset is one that contains the loan information of the prosper organisation. The data ranges from the details of people who have taken loans, the amount of loans taken, those paid and unpaid, and the returns of the organisation.It consists of 113,937 rows and 81 columns. It was obtained from Udacity hosted in the [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)


## Summary of Findings

I obtained a sample of the dataset by removing rows of null values in the variables chosen for analysis. These variables included loan status, employment status, borrower APR, borrower rate, estimated returns, on time prosper payments, income range and prosper principal borrowed.

In the exploration, I discovered that a large percentage of loans issued were current. It was closely followed by loans that were completely paid off. On the extremely lower end are loans that were cancelled and past due.The borrower rate distribution, estimated returns, and the borrower apr distribution variables had a normal distribution. This was visualized with a histogram. The on time prosper payments and ProsperPrincipalBorrowed variables on the other hand were highly skewed to the right. A log tranformation was applied on both of them to get more insight on the distribution. For the  on time prosper payments plot I concluded that a majority of borrowers had made on time payments less than 40 times and the most common loan amounts borrowed are below 20,000 dollars. Most of the loan borrowers were employed and had an income range of 50,000 - 74,999 dollars.

Most of the current loans were owned by the employed group of people and they also had the highest number of completed loans. Most defaulters belong to the Full time group. This means that employment is a major factor considered when issuing a loan. The borrower rate is highly correlated to the estimated returns of Prosper.Income range plays a significant role in making on time payments of their loans but is not highly reliant on employment status as even retired borrowers make their loans payments in time.The borrower rate is highly correlated to the estimated returns of Prosper. The borrower rate and borrower apr all show a positive correlation to estimated returns. An increase in the two variables means an increase in the expected returns. Majority of the loan borrowers had not completed their loans and were still current. They were still the majority who paid their loans on time and the principal amounts they borrowed varied.It is notable that they borrowed high amounts of loans as compared to other statuses.



## Key Insights for Presentation

For the presentation, I sought to discover the factors that affect the estimated returns for the prosper company. The major factors that were investigated were the borrower APR and borrower rate. I started by introducing the
distribution of the three variables using a histogram. Then I investigated the correlation between the borrower rate and the estimated returns. Finally I analysed all the three variables in one plot.


