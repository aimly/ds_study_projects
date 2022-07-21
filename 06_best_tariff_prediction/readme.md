# Best tariff prediction

The mobile operator found out: many customers use archived rates. A preliminary analysis of the use of tariffs on a sample of customers was carried out, the behavior of customers when using the operator's services was analyzed and the optimal sets of services for users were recommended. Hypotheses about the difference in revenue of subscribers of different tariffs and differences in the revenue of subscribers from Moscow and other regions. A profitable tariff plan has been identified for adjusting the advertising budget. A system has been developed that can analyze customer behavior and offer users a new tariff. A model has been built for the classification problem, which will select a suitable tariff. A model was built with the highest possible accuracy. The share of correct answers has been brought to 0.75. Accuracy was checked on the test sample.

## Structure of the report:

1. Review of data and  EDA
2. Data preprocessing
3. Model building
4. Test
5. Conclusion


## Columns:

- calls — number of calls,
- minutes — total duration of calls in minutes,
- messages — number of sms messages,
- mb_used - Internet traffic used in Mb,
- is_ultra - what tariff did you use during the month ("Ultra" - 1, "Smart" - 0)

## Used libraries

- pandas
- numpy
- sklearn
