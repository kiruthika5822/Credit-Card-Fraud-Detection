# Credit-Card-Fraud-Detection
**Credit Card Fraud Detection Project**

**Overview:**
This project aims to develop machine learning models for detecting fraudulent transactions in credit card data. The dataset contains information about transactions including transaction date, credit card number, merchant details, transaction amount, and whether the transaction is fraudulent or not.

**Project Goal:**
The primary goal of this project is to build and evaluate machine learning models that can accurately identify fraudulent transactions, thereby helping financial institutions minimize losses due to fraudulent activities.

**Dataset:**
The dataset used in this project consists of credit card transaction data with over 1.2 million records. Each record contains various features such as transaction date, credit card number, merchant details, transaction amount, and whether the transaction is fraudulent or not.

**Exploratory Data Analysis (EDA):**
During the EDA process, we analyzed the distribution of fraudulent vs. valid transactions, explored the relationship between transaction amount and fraud status, and investigated any patterns or anomalies in the data that could help in building predictive models.

**Model Evaluation:**
Three machine learning models were trained and evaluated using the dataset:
1. Logistic Regression
2. Decision Tree
3. Random Forest

**Model Performance:**
- Logistic Regression:
  - Accuracy: 99.61%
  - Precision: 0.0
  - Recall: 0.0
  - F1 Score: 0.0
  - ROC AUC Score: 0.5

- Decision Tree:
  - Accuracy: 99.58%
  - Precision: 0.47
  - Recall: 0.81
  - F1 Score: 0.60
  - ROC AUC Score: 0.90

- Random Forest:
  - Accuracy: 99.83%
  - Precision: 0.98
  - Recall: 0.58
  - F1 Score: 0.73
  - ROC AUC Score: 0.79

**Summary:**
- Logistic regression performed poorly with zero precision and recall.
- Decision tree and random forest models outperformed logistic regression.
- Random forest achieved the highest precision and accuracy among the three models.
- However, there's still room for improvement, especially in terms of recall.

**Next Steps:**
To further improve model performance, we can explore feature engineering, resampling techniques, hyperparameter tuning, and ensemble methods. Additionally, incorporating domain knowledge and exploring anomaly detection techniques could also enhance the model's ability to detect fraudulent transactions.

**Conclusion:**
This project demonstrates the importance of building accurate fraud detection models in the financial sector. By leveraging machine learning techniques, we can effectively identify and prevent fraudulent activities, thereby safeguarding financial institutions and their customers from potential losses.
