# CRM-Customer-Churn-Score

In the banking industry, customers have various options to fulfill their financial needs, including choosing from various institutions. With customers highly discerning about service quality, even a single negative experience can impact their perception of the entire bank. Banking services have become integral to daily life, with even short disruptions causing anxiety, underscoring our reliance on these services. Given the high cost of acquiring customers, analyzing churn becomes crucial. The churn rate measures the proportion of customers who terminate or do not renew their subscriptions, directly affecting revenue. Insights from churn analysis inform strategic decisions, enabling targeted actions to enhance service quality and customer experience, fostering trust and loyalty. Thus, predictive modeling and detailed churn analysis are imperative for sustainable growth in the banking sector.

#### Aim:
- To classify the potential churn customers based on numerical and categorical features.
- It is a binary classification problem for an imbalanced dataset.
- This notebook uses this [Kaggle Code as a referent](https://www.kaggle.com/code/simgeerek/churn-prediction-using-machine-learning/notebook#%C2%A04--Model-Tuning)

### Data Set Story:
The dataset was downloaded from Kaggle, an online platform for data scientists, machine learning enthusiasts, and related professionals. Its use is strictly didactic. For more information about the dataset, see the following link: [Bank Customers](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers/data)

- It consists of 10000 observations and 12 variables.
- Independent variables contain information about customers.
- The dependent variable refers to customer abandonment.

### Features:
- Surname: Surname
- CreditScore: Credit score
- Geography: Country (Germany / France / Spain)
- Gender: Gender (Female / Male)
- Age: Age
- Tenure: How many years of customer
- Balance: Balance
- NumOfProducts: Bank product used
- HasCrCard: Credit card status (0 = No, 1 = Yes)
- IsActiveMember: Active membership status (0 = No, 1 = Yes)
- EstimatedSalary: Estimated salary
- Exited: Abandoned or not? (0 = No, 1 = Yes)

## Pre-requirements

Before running CustomerChurn, make sure you have the following requirements:

- Python 3.9 or higher
  

## Run Environment

Everything was developed into a Google Colab Notebook for the project's current version. However, a local version (.py) will be deployed sooner.

