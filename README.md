# Project on Supervised Models

Campaign for selling personal loans - Description

This case is about a bank (Thera Bank) which has a growing customer base. Majority of these customers are liability customers (depositors) with varying size of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget.
The department wants to build a model that will help them identify the potential customers who have higher probability of purchasing the loan. This will increase the success ratio while at the same time reduce the cost of the campaign.
The file Bank.xls contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.


# Column descriptions 

1. ID - Customer ID 
2. Age-  Customer's age in completed years 
3. Experience - #years of professional experience 
4. Income -  Annual income of the customer ($000) 
5. ZIPCode - Home Address ZIP code. 
6. Family - Family size of the customer 
7. CCAvg - Avg. spending on credit cards per month ($000) 
8. Education - Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional 
9. Mortgage -  Value of house mortgage if any. ($000) 
10. Personal Loan - Did this customer accept the personal loan offered in the last campaign? 
11. Securities - Account Does the customer have a securities account with the bank? 
12. CD Account - Does the customer have a certificate of deposit (CD) account with the bank? 
13. Online - Does the customer use internet banking facilities? 
14. CreditCard -  Does the customer uses a credit card

# Considering the information provided above, follow the steps given below --
     
1. Read the column description and ensure you understand each attribute well 
2. Study the data distribution in each attribute, share your findings.
3. Get the target column distribution. Your comments 
4. Split the data into training and test set in the ratio of 70:30 respectively 
5. Use different classification models (Logistic, K-NN and Naïve Bayes) to predict the likelihood of a liability customer buying personal loans
6. Print the confusion matrix for all the above models
7. Give your reasoning on which is the best model in this case and why it performs better?

# Links:
 [Data](https://github.com/sivaole/PersonalLoanModel/blob/master/Bank_Personal_Loan_Modelling.csv)  
 [Link to the report(detailed analysis) - Report](https://github.com/sivaole/PersonalLoanModel/blob/master/Bank_Personal_Loan_Modelling%20Analysis%20Report.docx)   
 [Source code](https://github.com/sivaole/PersonalLoanModel/blob/master/Bank_Personal_Loans_Campaign_Modelling.ipynb)

# Developer:
Sivasankar Vennala
