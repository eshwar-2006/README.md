# README.md
# CODSOFT-TASK-2
### CREDIT CARD FRAUD DETECTION

This project focuses on detecting fraudulent credit card transactions using machine learning. The dataset is highly imbalanced, with very few fraud cases compared to non-fraud ones. The goal is to build a model that can accurately identify these rare fraud transactions and help prevent financial loss.

### About the Dataset

This dataset contains detailed records of credit card transactions made by customers over time. It is used to build models that can detect fraudulent transactions based on patterns in the data.

📁 File Used: fraudTrain.csv

📦 Size: ~351 MB

📄 Columns: 23 in total (e.g., transaction date, amount, merchant, category, etc.)

### Key Features in the Dataset

trans_date_trans_time: Date and time when the transaction occurred

cc_num: Anonymized credit card number of the customer

merchant: Name of the merchant where the transaction took place

category: Category of the merchant (e.g., gas_transport, grocery_pos)

amt: Amount of the transaction

first / last: First and last name of the credit card holder

gender: Gender of the cardholder (Male or Female)

street, city, state, zip: Address details of the cardholder

dob: Date of birth of the cardholder

trans_num: Unique transaction ID

unix_time: Transaction time in Unix timestamp format

is_fraud: Target column – 1 for fraudulent transaction, 0 for legitimate transaction

### Target

The main objective is to predict whether a transaction is fraudulent (is_fraud = 1) or legitimate (is_fraud = 0) using the given features.


### Usage

1.Detects fraudulent credit card transactions by analyzing transaction patterns and user behavior.

2.Helps financial institutions prevent fraud in real-time and reduce monetary losses.

3.Used to train and evaluate machine learning models for binary classification problems (fraud vs. non-fraud).

### Model Training

Three  models are used

1.Logistic Regression

2.Decision Tree

3. Random Forest

Each model was evaluated on four metrics:

Accuracy

Precision (Macro Average)

Recall (Macro Average)

F1-Score (Macro Average)

### Accuracy

Logistic regression accuracy:0.9936

Decision tree accuaracy:0.9958

Random Forest accuaracy: 0.9974

**BEST MODEL OF CREDIT CARD FRAUD DETECTION: RANDOM FOREST MODEL WITH HIGH ACCUACY OF 99.7%**

### Contributors 

Thalluru Lakshmi Prasanna


### Future Scope

1.Integrate advanced models like deep learning, LSTM, or Autoencoders for better fraud detection accuracy.

2.Use real-time data streaming to build live fraud monitoring systems for immediate alerts.

3.Include additional features like IP address, device ID, or transaction location to improve model performance.

4.Deploy the model as a web service or API to integrate with banking and financial platforms.
