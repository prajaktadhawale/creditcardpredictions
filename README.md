# creditcardpredictions

I obtained the dataset from [leaps.analyttica.com](https://leaps.analyttica.com/home). The dataset includes information about 10,000 bank customers with 18 features, such as age, salary, marital status, and credit card details. The primary objective is to predict customer churn, with only 16.07% of customers having churned.

## Project Summary

This project assists a bank manager in predicting customer churn to enable proactive measures for customer retention. Leveraging machine learning techniques, the goal is to build a predictive model based on demographic and financial factors. The project involves data exploration, preprocessing, model training, and evaluation.

## Dataset Details

- Data Source: [leaps.analyttica.com](https://leaps.analyttica.com/home)
- Features: CLIENTNUM, Attrition_Flag, Customer_Age, Gender, ... (and so on)

### Data Dictionary

| Column                    | Description                                             |
| ------------------------- | ------------------------------------------------------- |
| CLIENTNUM                 | Unique identifier for the customer holding the account  |
| Attrition_Flag            | 1 if the account is closed (churned), else 0            |
| Customer_Age              | Customer's Age in Years                                 |
| Gender                    | M=Male, F=Female                                        |
| Dependent_count           | Number of dependents                                    |
| Education_Level           | Educational Qualification of the account holder          |
| Marital_Status            | Marital status (Married, Single, Divorced, Unknown)      |
| Income_Category           | Annual Income Category of the account holder             |
| Card_Category             | Type of Card (Blue, Silver, Gold, Platinum)              |
| Months_on_book            | Period of relationship with the bank                    |
| Total_Relationship_count  | Total number of products held by the customer           |
| Months_Inactive_12_mon    | Number of months inactive in the last 12 months         |
| Contacts_Count_12_mon     | Number of contacts in the last 12 months                |
| Credit_Limit              | Credit Limit on the Credit Card                          |
| Total_Revolving_Bal       | Total Revolving Balance on the Credit Card               |
| Avg_Open_To_Buy           | Open to Buy Credit Line (Average of last 12 months)    |
| Total_Amt_Chng_Q4_Q1      | Change in Transaction Amount (Q4 over Q1)              |
| Total_Trans_Amt           | Total Transaction Amount (Last 12 months)               |
| Total_Trans_Ct            | Total Transaction Count (Last 12 months)                |
| Total_Ct_Chng_Q4_Q1       | Change in Transaction Count (Q4 over Q1)               |
| Avg_Utilization_Ratio     | Average Card Utilization Ratio                           |
