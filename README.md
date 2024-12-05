# Predict Telco customer churn using EDA and Machine Learning

The goal of this assignment is to understand the logic and methods of exploratory data analysis (EDA).
The mode of analysis is concerned with discovery, exploration, and empirically detecting phenomena in
data. EDA has become the default pre-modeling step for every Machine Learning project engagement.
Exploratory Data Analysis (EDA) is a way to investigate datasets and find preliminary information,
insights, or uncover underlying patterns in the data. Instead of making assumptions, data can be
processed in a systematic method to gain insights and make informed decisions. 

Prior commencing your efforts on coding, you must install the following libraries: 
- Pandas Profiling
- SweetViz

Performing Explanatory Data Analysis (EDA) on Customer Churn data within the Telecommunication
industry. Although there will be no need to build a model based on the data provided, you are asked to
look for issues in the data and find correlation among the various variables in order to improve/lower
customer churn predictions. 

Churn rate is a critical metric of customer satisfaction. Low churn rates mean happy customers; high
churn rates mean customers are leaving you. A small rate of monthly/quarterly churn compounds over
time. 1% monthly churn quickly translates to almost 12% yearly churn. 

Reader should focus on predicting customer churn rate. 

# Telco-Customer-Churn data:-
* CustomerID: Customer ID unique for each customer
* gender: Whether the customer is a male or a female
* SeniorCitizen: Whether the customer is a senior citizen or not (1, 0)
* Partner: Whether the customer has a partner or not (Yes, No)
* Dependent: Whether the customer has dependents or not (Yes, No)
* PhoneService: Whether the customer has a phone service or not (Yes, No)
* MultipeLines: Whether the customer has multiple lines or not (Yes, No, No phone service)
* InternetService: Customer’s internet service provider (DSL, Fiber optic, No)
* OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service)
* OnlineBackup: Whether the customer has an online backup or not (Yes, No, No internet service)
* DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service)
* TechSupport: Whether the customer has tech support or not (Yes, No, No internet service)
* StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
* StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service)
* Contract: The contract term of the customer (Month-to-month, One year, Two years)
* PaperlessBilling: The contract term of the customer (Month-to-month, One year, Two years)
* PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
* Tenure: Number of months the customer has stayed with the company
* MonthlyCharges: The amount charged to the customer monthly
* TotalCharges: The total amount charged to the customer
* Churn: Whether the customer churned or not (Yes or No)

# The reader can find 4 steps in "Janapana project 1"
* Prepared the data in order to be ready to be fed to a model. Looked for missing, null, NaN records. Finding outliers. Transform data – all entries should be numeric.
* Listed all types of data, numeric, categorical, text.
* Performed EDA. Presented dependencies and correlations among the various features in the data. Listed the most important variables (Feature Importance) that will affect the target label.
* Split the dataset into training and test datasets (80/20 ratio). Using SweetViz’s ‘compare’ command contrast the training vs test datasets on the target (‘churn’)

# In Janapana project 2

Used Data Science and AI approaches to predict which of the customers will be loyal and which will
lapse. Your ML model(s) will help the company’s executives to understand what makes a great or bad
customer so they can take action. 

# You will observe the performance of two (2) stages of analysis, based on different distribution of data:
1) Fit your models on the original (given) dataset
2) Fit your models on the modified dataset, after applying the SMOTE technique.

# The Machine Learning models used are: 
* Naïve Bayes
* Logistic Regression
* Random Forests
* XGBoost 

# The metrics of performance of the chosen models should be, with huge emphasis to recall: 
* Accuracy
* Precision
* Recall
* F1-Score 

# You will follow the standard ML workflow process while building your models: 
* Explanatory Data Analysis (already done!)
* Data Visualization (already done!)
* Data Preprocessing (Data Imputation, Feature Selection & Scaling, Encode Categorical Features)
* Address Data Imbalance (apply the SMOTE technique)
* Split the training/test datasets in the 80/20 % ratio
* Algorithm Selection
* Modeling Building
* Modeling Evaluation
* Model Tuning (Hyperparameters Tuning) 
