# Lending Club Case Study
> In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
    - You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

    If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

    If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- When a person applies for a loan, there are two types of decisions that could be taken by the company:

    Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

    Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

    Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

    Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

    Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
 
- The business probem that project is trying to solve:
    Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
    If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- What is the dataset that is being used?
    The loan dataset contains the complete loan data for all loans issued through the time period 2007 t0 2011.


## Conclusions from univariate analysis of Continuous columns
- Most of the loan amount lies in range of 5000-15000
- Installments lies in the range of 200-420
- DTI lies in the range of 8-19
- open_acc lies in range of 6-12
- Revol_bal lies in the range of 2000-19000
- total_acc lies in the range of 15-28
- total_payment lies in the range of 7000-18000

## Conclusions from univariate analysis of Categorical columns
- Most number of loans are taken for a tenure of 36 months
- Persons belonging to grade B takes the most number of loans and person belonging to grade G take   least number of loans


## Technologies Used
- jupyter 
- python 
- git 



## Contact
Created by [https://github.com/gupta-palash] - feel free to contact me!


