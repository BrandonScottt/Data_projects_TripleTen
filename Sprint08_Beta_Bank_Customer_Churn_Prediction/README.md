## Project Description
Beta Bank is facing an issue with customer churn, as customers are gradually leaving the bank. To address this, the goal of this project is to build a machine learning model that can predict whether a customer will leave the bank soon. By accurately predicting churn, Beta Bank can focus on retaining existing customers, which is more cost-effective than acquiring new ones.

The key objective is to develop a model with the highest possible F1 score, achieving a minimum threshold of 0.59 on the test set. Additionally, the AUC-ROC metric will be measured and compared with the F1 score to evaluate the model's performance.

## Data Description
The dataset is located at `/datasets/Churn.csv` and contains the following features:

- **RowNumber**: Data string index
- **CustomerId**: Unique customer identifier
- **Surname**: Customer's surname
- **CreditScore**: Credit score
- **Geography**: Country of residence
- **Gender**: Gender
- **Age**: Age
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Account balance
- **NumOfProducts**: Number of banking products used by the customer
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No)
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No)
- **EstimatedSalary**: Estimated salary
- **Exited**: Target variable indicating if the customer has left the bank (1 = Yes, 0 = No)

## Answer these questions:
- Examine the balance of classes. Train the model without taking into account the imbalance. Briefly describe your findings.
- Improve the quality of the model. Make sure you use at least two approaches to fixing class imbalance. Use the training set to pick the best parameters.
- Train different models on training and validation sets. Find the best one. Briefly describe your findings.
- Perform the final testing.
