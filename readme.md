## Project Summary

The project is focused on building a classification model to predict whether a customer will churn their credit card services. The project uses Python and several libraries, including Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and XGBoost.

### Business Context

The Thera bank recently saw a steep decline in the number of users of their credit card, which is a good source of income for banks. Customers leaving credit card services would lead the bank to loss, so the bank wants to analyze the data of customers and identify the customers who will leave their credit card services and the reason for the same – so that the bank could improve upon those areas.

### Data Description

The dataset used in this project contains the following columns:

* CLIENTNUM: Client number. Unique identifier for the customer holding the account
* Attrition_Flag: Internal event (customer activity) variable - if the account is closed then "Attrited Customer" else "Existing Customer"
* Customer_Age: Age in Years
* Gender: Gender of the account holder
* Dependent_count: Number of dependents
* Education_Level: Educational Qualification of the account holder - Graduate, High School, Unknown, Uneducated, College(refers to college student), Post-Graduate, Doctorate
* Marital_Status: Marital Status of the account holder
* Income_Category: Annual Income Category of the account holder
* Card_Category: Type of Card
* Months_on_book: Period of relationship with the bank (in months)
* Total_Relationship_Count: Total no. of products held by the customer
* Months_Inactive_12_mon: No. of months inactive in the last 12 months
* Contacts_Count_12_mon: No. of Contacts in the last 12 months
* Credit_Limit: Credit Limit on the Credit Card
* Total_Revolving_Bal: Total Revolving Balance on the Credit Card
* Avg_Open_To_Buy: Open to Buy Credit Line (Average of last 12 months)
* Total_Amt_Chng_Q4_Q1: Change in Transaction Amount (Q4 over Q1)
* Total_Trans_Amt: Total Transaction Amount (Last 12 months)
* Total_Trans_Ct: Total Transaction Count (Last 12 months)
* Total_Ct_Chng_Q4_Q1: Change in Transaction Count (Q4 over Q1)
* Avg_Utilization_Ratio: Average Card Utilization Ratio

### Libraries Used

The following libraries were used in this project:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

### Conclusion

The project provides a comprehensive example of how to approach a classification problem using Python and various machine learning libraries. The notebook explores the data, performs data cleaning and preprocessing, performs exploratory data analysis (EDA), builds and evaluates several machine learning models, selects the best-performing model, and performs hyperparameter tuning to optimize its performance. The optimized model is then used to make predictions on a test set, and the results are evaluated using various metrics.