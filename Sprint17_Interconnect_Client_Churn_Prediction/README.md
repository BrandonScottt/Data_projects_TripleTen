## Project Overview

Interconnect, a telecom operator, aims to forecast client churn to proactively retain customers by offering promotional codes and special plans. This project involves analyzing client data to predict whether a user is likely to leave, using various personal and service-related information.

## Data Description
The dataset consists of customer information across multiple categories:

- **`customerID`**: Unique ID assigned to each customer.
- **`gender`**: Gender of the customer.
- **`SeniorCitizen`**: Indicates whether the customer is a senior citizen.
- **`Partner`**: Indicates whether the customer has a partner.
- **`Dependents`**: Number of dependents the customer has.
- **`BeginDate`**: Date the customer joined the service.
- **`EndDate`**: Date the customer ended the service.
- **`Type`**: Plan type selected by the customer.
- **`PaperlessBilling`**: Indicates whether the customer uses paperless billing.
- **`PaymentMethod`**: Method of payment used by the customer.
- **`MonthlyCharges`**: Monthly charges billed to the customer.
- **`TotalCharges`**: Total charges billed to the customer over the duration of the service.
- **`MultipleLines`**: Indicates whether the customer has multiple phone lines.
- **`InternetService`**: Indicates whether the customer has internet service.
- **`OnlineSecurity`**: Indicates whether the customer has online security.
- **`OnlineBackup`**: Indicates whether the customer has online backup.
- **`DeviceProtection`**: Indicates whether the customer has device protection.
- **`TechSupport`**: Indicates whether the customer has tech support.
- **`StreamingTV`**: Indicates whether the customer has streaming TV service.
- **`StreamingMovies`**: Indicates whether the customer has streaming movie service.
- **`is_churned`**: Target variable, indicates whether the customer has churned.
- **`num_days`**: Number of days the customer has been in the system.
- **`year`**: Year of data entry.
- **`num_services`**: Number of services the customer has availed.

## Answer these questions:
- Perform data analysis.
- Create new features and clean the data.
- Build different models and perform hyperparameter tuning with cross validation
