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
- ![image](https://user-images.githubusercontent.com/94292484/168279625-44f93ce5-d196-4a13-b7a0-de7997851fd9.png)
2. Client who have management, technician, blue-collar, admin and retired jobs are more subscribed to term deposits than other jobs
- ![image](https://user-images.githubusercontent.com/94292484/168281251-abdd1469-ff76-491b-aa64-4549f55f45f2.png)
# ML Modelling
Before we train the model, split the data into train set & test set (size is 30%). Trained the model with 5 different algorithms and evaluated them with AUC score and Precision. AUC score used to make the model ideal for the dataset.Precision used to minimize subscribed client wrong predictions so the marketing cost can be reduced. The model was trained with:
- Logistic Regression
- Decision Tree
- XGboost
- KNN
- Random Forest
# Model Evaluation
![image](https://user-images.githubusercontent.com/94292484/168284351-c06a0969-a1f1-4dd4-979b-e0f18c3f4e50.png)
