# Borrowers reliability investigation

The customer is the credit department of the bank. It is necessary to understand whether the marital status and the number of children 
of the client affect the fact of repayment of the loan on time. Input data from the bank — statistics on the solvency of customers.
The results of the study will be taken into account when building a credit scoring model — a special system that evaluates the ability 
of a potential borrower to repay a loan to a bank.

## Structure of the report:

1. Review of data and little EDA
2. Data preprocessing
3. Building and checking hypothesis
4. Conclusion

## Columns:

- **children** — the number of children in the family
- **days_employed** — total work experience in days
- **dob_years** — client's age in years
- **education** — the level of education of the client
- **education_id** — identifier of the level of education
- **family_status** — marital status
- **family_status_id** — id of marital status
- **gender — gender** of the client
- **income_type** — type of employment
- **debt — whether** there was a debt on repayment of loans
- **total_income** — monthly income
- **purpose** — the purpose of obtaining a loan

## Tools used
- pandas
- numpy
- matplotlib
- plotly
