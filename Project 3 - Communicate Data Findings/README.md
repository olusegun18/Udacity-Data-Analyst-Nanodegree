# Diamonds Data Exploration

## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The aim of this project is to use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns, and relationships.

The data can be found here [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000), with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

In the exploration, I found that most people took loans for debt consolidation. About 50% of the borrowers borrowed to consolidate debt. Only about 7% took loans for business purposes. The top five states represented are CA - California, TX - Texas, NY - New York, FL - Florida, IL - Illinois. Most of the borrowers are rated C (which is low-grade); this means the credit agency took more risk than normal. I also discovered that the distribution of monthly income feature is skewed to the right while the principal feature is multi-modal but the Principal feature looked more "Normal" after a log transformation was applied. The credit agency had negative returns on some loans due to incomplete payment. But only 195 of them resulted in negative returns. More than 30% of the loans were listed in 2013 and it's by far greater than other years in the data. Usurprisingly, there is a positive relationship between the Annual Percentage Rate on the loan and return on the loan for the credit agency. Also, the data shows that the lower the rating, the more the APR and the more the likelihood of default. And lastly, borrowers rated B, C and D yielded the highest returns for the credit agency


## Key Insights for Presentation

For the presentation, I focus on just some basic introduction about the behaviour of the clients. The reason for taking the loans, the most represnted credit rating and the states the borrowers identified with. After that, I used bivariate and multivariate exploration using scatterplots and heatmaps to deduce relationships between some of the variables in the dataset.