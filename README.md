# Lending Club Case

## Problem Statement:
* Lending club house provides various types of loans to applicants. Now, when these lending houses receives the loan application there can be two deisions 
  * Accept the loan application, if company accept loan application for customer having tendency to default, company will loose money.
  * Reject the loan application, if company rejects the loan application for customer who can repay the loan, company will loose business.
* Driving factors or attributes for lending club to understand customer who can possibly default loan.

## Solution
* The attached notebook have work analysing the given loan data **(2007-2011)** to undertstand the consumer and loan attribute that can potentially help lending club houses to figure out tendency of defaulting the loan.
* The solution for above proplem statement has been done using the **EDA** (Univariate and Bivariate) analysis.

## EDA Analysis
* All the columns who do not have any values have been dropped like (**'verification_status_joint', 'total_bal_il', 'open_acc_6m'** etc).
* The irrevelant columns for our analysis have been dropped like (**'delinq_2yrs', 'earliest_cr_line', 'inq_last_6mths', 'open_acc'** etc).

## Univariate Analysis:
* Analysed the single column to understand the data and it's distribution etc that helps to understand the data 
* For instance:

    * loan terms 36 and 60 months 
      ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_term.png)
    * loan status types
      ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status.png)
    * Home Owner Ship Types etc
      ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/home_ownership.png)
    * Loan Installment
      ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/installment.png)
    * Loan Amount
      ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_amnt.png)

## Bivariate Analysis:
* Analysed the two columns one column being 'loan_status' against the other columns 

  * loan_status vs installment
  ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status_vs_installment.png)
  * loan_status vs term
  ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status_vs_term.png)
  * loan_status vs loan_amnt
  ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status_vs_loan_amnt.png)
  * loan_status vs funded_amt
  ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status_vs_funded_amnt.png)
  * loan_status vs funded_amnt_inv
  ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status_vs_funded_amnt_inv.png)
  * loan_status vs annual_inc
  ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status_vs_annual_inc.png)
  * loan_status vs home_ownership 
  ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status_vs_home_ownership.png)
  * loan_status vs addr_state
  ![alt text](https://github.com/rohit2503/lending-club-case/blob/main/images/loan_status_vs_addr_state.png)
  
