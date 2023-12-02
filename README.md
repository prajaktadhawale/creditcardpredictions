# creditcardpredictions

I obtained the dataset from [leaps.analyttica.com](https://leaps.analyttica.com/home). The dataset includes information about 10,000 bank customers with 18 features, such as age, salary, marital status, and credit card details. The primary objective is to predict customer churn, with only 16.07% of customers having churned.

## Project Summary

This project assists a bank manager in predicting customer churn to enable proactive measures for customer retention. Leveraging machine learning techniques, the goal is to build a predictive model based on demographic and financial factors. The project involves data exploration, preprocessing, model training, and evaluation.

## Dataset Details

- Data Source: [leaps.analyttica.com](https://leaps.analyttica.com/home)
- Features: CLIENTNUM, Attrition_Flag, Customer_Age, Gender, ... (and so on)

### Data Dictionary

| Column                        | Description                                              |
| ----------------------------- | -------------------------------------------------------- |
| CLIENTNUM                     | Unique identifier for the customer holding the account   |
| Attrition_Flag                | 1 if the account is closed (churned), else 0             |
| Customer_Age                  | Customer's Age in Years                                  |
| Gender                        | M=Male, F=Female                                         |
| ... (and so on)               | ...                                                      |
