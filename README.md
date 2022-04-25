# How to Retain Customers and Influence People
**Author:** Alexis Deviney

## Overview
This goal of this project is to recommend strategies to minimize customer churn (or service termination) from a fictional telecommunications company. In my analysis, I answered the following questions:
1. What customer demographics have the highest proportion of customer churn?
2. Is service/product engagement predictable of churn? Which products, when opted into, confer a lower probability of a customer to churn?
3. What services are the most profitable?
4. What is the tenure of customers who decide to churn? Are new or old customers churning?
6. Are longer contracts conducive to customer retention?

## Business Problem
Attracting new customers can be up to 5x more costly than retaining existing customers. 
Predict behavior to retain customers at Telco telecommunications company. Analyze all relevant customer data to help develop focused customer retention programs. 

## Data
I analyzed a data consisting of information on 7,043 unique customers and information relating to their demographics, account history, and services.

## Data Sources
Cognos Analytics Sample Datasets
* [Customer Churn](https://community.ibm.com/accelerators/catalog/content/Customer-churn)

* [Telco Customer Churn](https://community.ibm.com/accelerators/catalog/content/Telco-customer-churn)

* [Telco Customer Churn Status and Reason for Leaving](https://community.ibm.com/accelerators/catalog/content/Telco-customer-churn-status-and-reason-for-leaving)

### Variables and Engineered Features

Variables given in datasets:

|Variable Name|Description|
|---|---|
|CustomerID|Unique ID identifying customer|
|Gender|Customer's gender, Male or Female|
|SeniorCitizen|Indicates whether the customer is 65 years or older, Yes or No|
|Partner|Indicates whether the customer has a partner, Yes or No|
|Tenure|Total number of months the customer has been with the company|
|Latitude|The latitude of the customer's residence|
|Longitude|The longitude of the customer's residence|
|Zip Code|The zip code of the customer's residence|
|PhoneService|Indicates if the customer is subscribed to phone service with the company, Yes or No|
|MultipleLines|Indicates if  the customer has multiple phone lines on their phone service, Yes or No|
|InternetService|Indicates if the customer is subscribed to internet service with the company, Yes or No|
|OnlineSecurity|Indicates if the customer subscribes to an additional online security service provided by the company, Yes or No|
|OnlineBackup|Indicates if the customer subscribes to an additional online backup service provided by the company, Yes or No|
|DeviceProtection|Indicates if the customer subscribes to additional device protection service provided by the company, Yes or No|
|TechSupport|Indicates if the customer subscribes to a premium tech support service provided by the company, Yes or No|
|StreamingTV|Indicates if the customer uses their Internet service to stream TV, Yes or No|
|StreamingMovies|Indicates if the customer uses their Internet service to stream movies, Yes or No|
|Contract|Indicates the customer's contract type with the company: Month-to-month, One-year, or Two-year|
|PaperlessBilling|Indicates if the customer has opted into paperless billing, Yes or No|
|PaymentMethod|Indicates how the customer pays their bill: Electronic check, mailed check, automatic bank transfer, or automatic credit card|
|MonthlyCharges|Customer's current monthly charges for services provided by the company|
|TotalCharges|Sum of customer's charges to-date|
|Churn|Yes = The customer left the company this quarter. No = The customer remained with the company|
|Churn Reason|A customer's reason for leaving the company, selected from a list of structured options at service termination|




## Technical Presentation about Initial EDA

[Google Drive link](https://drive.google.com/file/d/19aR9KYIWNQG5ErrFV2ksu3sAiQFCIHpA/view?usp=sharing)
