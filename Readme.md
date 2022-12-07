# LendingClubCaseStudy

## Introduction :  
* Risk Analysis for a Consumer Finance company where we want to help company to take decisions to offer loan to a particular applicant or not. Risks are identified based on the applicant's profile.

## Methods Used:  Exploratory Data Analysis (EDA),  Data Visualization in Python.

## Procedure:
* On behalf of a consumer finance company which specialises in lending various types of loans to urban customers, the analysis will help the company to be in profit by providing or rejecting loan applications. When the company receives a loan application, It will make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

#### 1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
#### 2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

* The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

* In this case study, we used EDA to understand how consumer attributes and loan attributes influence the tendency of default.

* When a person applies for a loan, there are two types of decisions that could be taken by the company:

* a. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

* b. Fully paid: Applicant has fully paid the loan (the principal and the interest rate) Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Getting Started:
Clone this repo (for help see this tutorial).
* Data used for Analysis - loan.csv
* Description of data- Data_Dictionary.xlsx
* Python Code - LendingClubCaseStudy.ipynb

## Technologies Used:
* Python 
* Matplotlib
* Seaborn
* Numpy
* Pandas

## System Requirements:
* Windows
* Jupyter Notebook

## Contributors :
* Neelam Mahapatro (https://neelammahapatro.github.io/)
* Chinju K Raveendran (https://github.com/chinjukr)

## Ackowledgement:
* We would like thank IIIB UpGrad teams for providing us the opportunity to work on this Case Study.
