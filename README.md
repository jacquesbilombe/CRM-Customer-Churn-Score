# CRM-Customer-Churn-Score

In the banking industry, customers have various options to fulfill their financial needs, including choosing from a range of institutions. With customers highly discerning about service quality, even a single negative experience can impact their perception of the entire bank. Banking services have become integral to daily life, with even short disruptions causing anxiety, underscoring our reliance on these services. Given the high cost of acquiring customers, analyzing churn becomes crucial. The churn rate measures the proportion of customers who terminate or do not renew their subscriptions, directly affecting revenue. Insights from churn analysis inform strategic decisions, enabling targeted actions to enhance service quality and customer experience, fostering trust and loyalty. Thus, predictive modeling and detailed churn analysis are imperative for sustainable growth in the banking sector.

#### Aim:
- To classify the potential churn customers based on numerical and categorical features.
- It is a binary classification problem for an imbalanced dataset.

### Data Set Story:¶
- It consists of 10000 observations and 12 variables.
- Independent variables contain information about customers.
- The dependent variable refers to customer abandonment.
- 
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

## Prerequisites

Before running CustomerChurn, make sure you have the following requirements:

- Python 3.9 or higher
  

## Google Colab


## Local Installation

To get started with CustomerChurn, follow these steps:

### **1. Open a shell and clone this repo**

```bash
git clone https://github.com/jacquesbilombe/CRM-Customer-Churn-Score.git
```

### **2. Create CustomerChurn environment.**

#### **2.1 Install make.**
* **For Windows:**

  1- Open PowerShell (Windows + x)

  2- Install Chocolatey

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

  3- Verify Chocolatey install

```bash
choco
```

  4- Make install

```bash
choco install make
```

* **For Linux:**

  1- Make install

```bash
sudo apt install make
```

#### **2.2 Install Anaconda**
 
If you don't have Anaconda, see how to install it here https://docs.anaconda.com/anaconda/install/linux/

### **3. Conda Torus environment creation.**

Go to FashionClassifier/ folder and run the following code in Anaconda Prompt to create and install all pre-requirements

```bash
cd CustomerClassifier
make setup
```
Finally, activate the conda environment

```bash
conda activate churn
```
### **4. Run CustomerChurn**

```bash
python main.py FLAG "database.csv"
```

Terminal Example:

```bash
python main.py 0 "dataset.csv"
```

Obs: 
- FLAG: 0 to use the trained ML model and 1 to train the ML model again. 
- Dataset (Yours): if the line is empty "", the code will use the project dataset

------------
### All

- [ ] Token for automation.
