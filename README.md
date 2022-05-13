# Term Deposit Conversion Rate Prediction & Analysis : Project Overview
- Build a _machine learning_ model to predict client that subscribe term deposit
- Dataset is obtained from https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets/code
- Preprocessing the data from 'unknown' value with mode() for job, education, and contact features
- Handle data outliers with Z-score  
- Transform the data with StandardScaler()
- Engineered features to optimizing the learning process of model
- Split the data into train and test 70:30
- train the model with 5 different algorithms with hyperparameter tuning and choose the best algorithm 
- Handle imbalance class with Threshold Moving 
- Validate the model with data test 
## Problems
- Term Deposit are major source of income for a bank. Currently, Telephonic marketing campaigns is the most effective way to reach out to people. However, they require huge investment.
- Based on the data, the subscription rate of the client is relatively small which is 11.7%
## Purposes 
- The targeted client are successful in subscribing term deposit, while still optimizing marketing costs.
# Data Analysis
1. Distribution of Subscribed client is not balanced
![image](https://user-images.githubusercontent.com/94292484/168279625-44f93ce5-d196-4a13-b7a0-de7997851fd9.png)
2. Client who have management, technician, blue-collar, admin and retired jobs are more subscribed to term deposits than other jobs
3. ![image](https://user-images.githubusercontent.com/94292484/168281251-abdd1469-ff76-491b-aa64-4549f55f45f2.png)
