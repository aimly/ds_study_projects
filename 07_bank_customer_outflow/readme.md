# Bank customer outflow

Customers began to leave the bank. Every month. A little, but noticeable. Bank marketers have found that it is cheaper to retain current customers than to attract new ones.
It is necessary to predict whether the client will leave the bank in the near future or not. Historical data on the behavior of customers and termination of contracts with the bank are presented.

## Structure of the report:

1. Review of data and  EDA
2. Data preprocessing
3. Model building
4. Test
5. Conclusion


## Columns:

- RowNumber — index of the row in the data
- CustomerID — unique identifier of the customer
- Surname — last name
- CreditScore — credit rating
- Geography — country of residence
- Gender — gender
- Age — age
- Tenure — how many years person has been a customer of the bank
- Balance — account balance
- NumOfProducts — number of bank products used by the customer
- HasCrCard — availability of a credit card
- IsActiveMember — client activity
- EstimatedSalary — estimated salary
- Exited — the fact of the client's departure (target)

## Used libraries

- pandas
- numpy
- sklearn
