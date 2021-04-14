# D
Quick project on an exploring publicly available data from LendingClub.com from 2007 to 2010
This project has some data visualization to better understand the imported data and 
I am looking to understand what has more impact in wether someone will pay back the loan 
I created two models using decision trees and random forest to help predict this.

Data available as a csv file
Here are what the columns represent:

a) credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.

b) purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").

c) int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.

d) installment: The monthly installments owed by the borrower if the loan is funded.

e) log.annual.inc: The natural log of the self-reported annual income of the borrower.

f) dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).

g) fico: The FICO credit score of the borrower.

h) days.with.cr.line: The number of days the borrower has had a credit line.

i) revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).

j) revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).

k) inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.

l) delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.

m) pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).
