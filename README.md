# Credit-Card-Default-prediction-using-ML

The Credit Card Default Prediction problem is a classic binary classification task in the domain of financial risk modeling. The primary objective is to predict whether a customer will default on their credit card payment in the next billing cycle, based on their historical behavior and demographic information.

This prediction is crucial for banks and financial institutions to minimize credit risk. By identifying high-risk customers early, banks can take proactive measures such as adjusting credit limits, issuing warnings, or declining new credit offers.

The dataset used in this project is a real-world dataset that includes anonymized data of over 30,000 credit card clients. The features include:

Demographic information (e.g., age, sex, marital status)

Behavioral history (e.g., past bill amounts, payment history, payment status over six months)

The target variable is a binary indicator:

1 – the customer will default in the next month

0 – the customer will not default

The project starts with data preprocessing, where missing values are identified and handled (e.g., replacing missing age values with the median due to outliers). Next, exploratory data analysis (EDA) is conducted to understand the relationship between each feature and the likelihood of default. For instance:

Customers who consistently delay payments (PAY_0 to PAY_6) tend to have a higher chance of defaulting.

Sex and marriage status also show slight correlations, with female customers and certain marital statuses showing slightly higher default rates.

Age, however, does not show a significant difference in defaulters vs. non-defaulters.

The final goal is to build a machine learning model that not only predicts accurately but is also interpretable from a financial perspective—helping institutions understand the "why" behind predictions and enabling trust and compliance.

In summary, this project combines data science and financial domain knowledge to develop a tool for smarter, data-driven credit risk management.

