# Telecom companu tariff analysis

The mobile operator found out: many customers use archived rates. 
A preliminary analysis of the use of tariffs on a sample of customers was carried out, the behavior of customers when using the operator's services was 
analyzed and the optimal sets of services for users were recommended. Hypotheses about the difference in revenue of subscribers of different 
tariffs and differences in the revenue of subscribers from Moscow and other regions. A profitable tariff plan has been identified for adjusting 
the advertising budget. A system has been developed that can analyze customer behavior and offer users a new tariff. A model has been built for 
the classification problem, which will select a suitable tariff. A model was built with the highest possible accuracy. The share of correct answers 
has been brought to 0.75. Accuracy was checked on the test sample.


## Structure of the report:

1. Review of data and little EDA
2. Data preprocessing and data visualization
3. Building and checking hypothesis
4. Conclusion


## Columns:

Table users (information about users):
- user_id — unique user identification number
- first_name — user name
- last_name — user last name
- age — user age (years)
- reg_date — registration date (day, month, year)
- churn_date — date of stop using tariff (null means that user still client)
- city — user's city
- tariff


Table calls (information about calls):
- id — unique call identification number
- call_date — date of call
- duration — duration of call in minutes
- user_id — unique user identification number


Table messages (information about messages):
- id — unique message identification number
- message_date — date of message
- user_id — unique user identification number


Table internet (information about internet sessions):
- id — unique session identification number
- mb_used — amount of used traffic in megabytes
- session_date — date of internet session
- user_id — unique user identification number

Table tariffs (information about tariffs):
- tariff_name
- rub_monthly_fee — monthly subscription fee in rubles
- minutes_included - number of minutes of conversation per month included in subscription fee
- messages_included - number of messages per month included in subscription fee
- mb_per_month_included - the amount of internet traffic included in subscription fee (in megabytes)
- rub_per_minute - cost of a minute of conversation in excess of the tariff package (for example, if the tariff includes 100 minutes of conversation per month, then a fee will be charged from 101 minutes)
- rub_per_message - cost of sending a message in excess of the tariff package
- rub_per_gb - cost of an additional gigabyte of internet traffic in excess of the tariff package (1 gigabyte = 1024 megabytes)


## Used libraries

- Pandas
- Matplotlib
- numpy
- SciPy
- Seaborn
- sklearn
