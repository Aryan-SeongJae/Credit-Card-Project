
So we are working on "Default of Credit Card Clients Dataset" which contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005 and our goal is to estimate whether a person will default (fail to pay) their credit card bills. This dataset has 30,000 examples and 24 features. The column we are trying to predict is "default.payment.next.month". 


Features of the dataset:
1. ID: ID of each client
2. LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit)
3. SEX: Gender of the client
4. EDUCATION: Level of education
5. MARRIAGE: Marital status
6. AGE: Age in years
7. PAY_0 TO PAY_6: History of past payment. We tracked the past monthly payment records (from April to September, 2005)
8. BILL_AMT1 TO BILL_AMT6: Amount of bill statement (NT dollar). We tracked the bill statement records (from April to September, 2005)
9. PAY_AMT1 TO PAY_AMT6: Amount of previous payment (NT dollar). We tracked the payment records (from April to September, 2005)
10. default.payment.next.month: Default payment (1=yes, 0=no) {target}
