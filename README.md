# Principal Component and Factor Analysis

We will apply principal component analysis and factor analysis to multivariate data. The data is a sample from a dataset which has been used to predict credit card clients' default payments. There are demographic variables and behavior-history variables. Many of the behavioral variables are highly correlated, so not all of them can be used in a regression for prediction. Multivariate techniques help us understand the relationship among many variables in order to reduce the dimensionality of the data. The variables in current sample dataset are as follows.  

CUSTOMERID: 	Customer ID 
LIMIT_BAL:	 Credit limit
Education:	Education level
Age:	Customer age
PAY_1 to PAY_6:	6 months of payment history: -2 = 2 weeks before due, -1 = one week before due, 0 = in the due week,  +1 = one week after due, etc. 
BILL_AMT1 to BILL_AMT6:	6 months of billed amount
PAY_AMT1 to PAY_AMT6:	6 months of paid amount 
