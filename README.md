# Lending Club Case Study
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.


## Table of Contents
* General Info(#general-information)
* Tools & Technologies:(#technologies-used)
* Key Responsibilities:(#key-responsibilities)
* Conclusion:(#conclusion)


## General Information:
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company>
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the compy
The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate of "default".

Business Objectives:-To be able to identify risky loan applicants, so that such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
We want to showcase the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.


## Tools & Technologies:

Programming Language: Python 3
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Data Visualization Tools: Matplotlib, Seaborn
IDE: Anaconda Jupyter Notebook


## Key Responsibilities:

Data Collection and Preprocessing
- Missing Value Treatment
- Outlier detection and treating
- Removing unnecessary columns
Exploratory Data Analysis (EDA)
- Univariate Analysis
- Bivariate Analysis
	

## Conclusions
Minor Impact
	• Higher loan amount (above 16K) 
	• Higher installment amount (above 327)
	•Lower annual income (below 37K)
	•Higher debt to income ratio (above 15%)
	•Applicant’s address state (NV, SD, AK, FL, etc.)
	•Loan issue month (May, Sep)

Heavy impact
	•Higher interest rate (above 13%)
	•Higher revolving line utilization rate (above 58%) 
	•Repayment term (5 years)
	•Loan grade & sub-grade (D to G)
	•Missing employment record
	•Loan purpose (small business, renewable energy, educational)
	•Derogatory public records (1 or 2)
	•Public bankruptcy records (1 or 2)

Combined impact
	•High loan amount & interest rate for lower income group
	•High installment and longer repayment term 
	•Home ownership (other) and loan purpose (car, moving or small business)
	•Residential state and loan purpose
	•Income group and loan purpose

## Contact
Created by Jyoti Panda,PrajwalKR93 - feel free to contact us!