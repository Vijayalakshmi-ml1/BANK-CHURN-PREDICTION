# BANK-CHURN-PREDICTION
project objective:
In this project, I will be performing an classification of data on the customer's records from a bank database.The aim of this project is to identify key factors contributing to customer attrition in a consumer credit card portfolio and to develop a classification model that can accurately predict customers who are likely to churn.Customer churn is a critical concern for the business, as acquiring new customers is significantly more costly than retaining existing ones. By understanding the patterns and behaviors that lead to attrition, the business can proactively intervene and improve customer retention.

methodology:
here we collected data  about Customers who Attired,
Services that each customer using – Type of credit Card , Total no. of products held by the customer.
Customer credit information - how long they’ve been a customer, No. of months inactive in the last 12 months, Credit Limit on the Credit Card, Total Revolving Balance on the Credit Card, Open to Buy Credit Line (Average of last 12 months), Total Transaction Amount ,Total Transaction Count and Average Card Utilization Ratio.
Demographic info about customers – gender,income range, age, and if they have partners and dependents
here data is very imbalanced. so we used the technique such as smote,reduced dimensionality using PCA without loosing large information,did encoding of categorical variables.standerdize data ,used voting classifier to enhance output.

result:
 The final voting classifier model achieved an R² score of 0.87, indicating that approximately 87% of the variance in churning can be explained by the model. Overall, these results suggest that the model is a robust and reliable tool for predicting churning based on the given features.
