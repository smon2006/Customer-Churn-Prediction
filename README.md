# Customer Churn Prediction using Artificial Neural Networks (ANN)

### Overview

This project implements a binary classification model using **Artificial Neural Networks (ANN)** to predict whether a bank customer will leave (churn) or stay with the bank. It utilizes the **Churn Modelling Dataset** for training and evaluation to identify key factors that lead to customer attrition.

### About the Dataset

The project uses the **Churn Modelling Dataset**, which contains details of 10,000 bank customers. The features include demographic information and financial behavior recorded by the bank.

#### Attribute Information:

* **RowNumber:** Row index.
* **CustomerId:** Unique identifier for the customer.
* **Surname:** Customer's last name.
* **CreditScore:** Numerical value representing creditworthiness.
* **Geography:** Customer's location (France, Spain, Germany).
* **Gender:** Male or Female.
* **Age:** Customer's age.
* **Tenure:** Number of years the customer has been with the bank.
* **Balance:** Amount of money in the account.
* **NumOfProducts:** Number of products the customer has purchased through the bank.
* **HasCrCard:** Whether the customer has a credit card (1 = Yes, 0 = No).
* **IsActiveMember:** Whether the customer is an active member (1 = Yes, 0 = No).
* **EstimatedSalary:** Customer's annual salary.
* **Exited (Target):** Whether the customer left the bank (1 = Yes, 0 = No).
* **Missing attribute values:** None
* **Class distribution:**  7,963 customers stayed (0) , 2,037 customers exited (1)



### Model and Approach

* **Algorithm:** Artificial Neural Network (ANN) with multiple Dense and Dropout layers.
* **Preprocessing:** One-Hot Encoding for categorical variables (Geography, Gender) and Standard Scaling for numerical features.
* **Train-Test Split:** 80%–20%.
* **Performance Metrics:**
* Accuracy Score
* ROC AUC Score
* F1-Score



### Installation & Dependencies

Ensure you have Python and the required libraries installed before running the code.

#### Required Libraries

```bash
pip install numpy pandas matplotlib seaborn tensorflow scikit-learn

```

### Usage
1. **Clone the repository:**
```bash
git clone https://github.com/your-username/Customer_Churn_Prediction.git
cd Customer_Churn_Prediction

```


2. **Open the Jupyter Notebook:**
Launch Jupyter Lab or Notebook:
```bash
jupyter notebook

```


3. **Run Cells:**
Open `customer_churn_model.ipynb` and run the cells sequentially to see the data analysis and train the model.
