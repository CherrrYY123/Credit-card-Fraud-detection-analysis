# Credit-card-Fraud-detection-analysis
`Data link` : [https://www.kaggle.com/datasets/neharoychoudhury/credit-card-fraud-data]

### To visualise the interactive plots using plotly, refer:
`Code link` : [https://www.kaggle.com/code/neharoychoudhury/credit-card-fraud-detection-analysis]

## Overview
The Credit Card Fraud Prediction project aims to develop a machine learning-based system to detect fraudulent transactions. By analyzing various features of credit card transactions, the goal is to create a model that accurately identifies fraudulent activities, helping to reduce financial losses and enhance transaction security.

## Dataset
The dataset used in this project includes credit card transactions from the western United States. It contains 14,446 entries with the following columns:

- trans_date_trans_time: The exact date and time of the transaction.
- amt: The transaction amount.
- city: Customer's city.
- state: Customer's state.
- lat: Latitude of the customer's location.
- long: Longitude of the customer's location.
- dob: Customer's date of birth (used to derive age).
- is_fraud: Binary indicator (0 or 1) of whether the transaction was fraudulent.


## Libraries
This project utilizes various Python libraries:

- pandas: For data manipulation and analysis.
- numpy: For numerical operations.
- seaborn: For statistical data visualization.
- matplotlib.pyplot: For static plotting.
- plotly.express and plotly.graph_objects: For interactive visualizations.
- scikit-learn: For machine learning, including:
- train_test_split and GridSearchCV for model evaluation and hyperparameter tuning.
- accuracy_score, classification_report, and confusion_matrix for performance metrics.
- LogisticRegression, SVC, and RandomForestClassifier for classification algorithms.
- LabelEncoder and StandardScaler for data preprocessing.

