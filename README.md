# CRM-Customer-Churn-Score

Churn score analysis predicts the likelihood of customers discontinuing their relationship with a business. By analyzing various customer attributes and behaviors, such as transaction frequency, engagement levels, and demographic information, businesses can assign a churn score to each customer. This score helps identify high-risk customers who may need intervention strategies to prevent churn. Advanced machine learning techniques are often used to develop predictive models for churn scoring, enabling businesses to proactively address customer retention challenges and enhance overall customer satisfaction and loyalty.

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
