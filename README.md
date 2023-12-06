# Mini_Capstone_Project_Bank_Marketing_Analysis

**The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls.**

# Aim of the project
#### To do exploratory data analysis(EDA) and visualisation of bank marketing dataset.
#### Also find out which campaign's performance is better than another.(Effectiveness of Campaign) 

# Variables in dataset

| |  Variables  | Type    | Details   | 
|---:|:-------------|:-----------|:------|
| 1 | age  | Numeric       | per capita crime rate by town  | 
| 2 | job  | Categorical   | type of job admin.","blue-collar","entrepreneur","housemaid","management","retired","self-employed","services","student","technician","unemployed","unknown") | 
| 3 | marital  | Categorical    | marital status ("divorced","married","single","unknown"; note: "divorced" means divorced or widowed)   |
| 4 | education  | Categorical    | ("basic.4y","basic.6y","basic.9y","high.school","illiterate","professional.course","university.degree","unknown")   | 
| 5 | default  | Categorical   | Does the customer have credit in default? ( "no","yes","unknown")   | 
| 6 | balance  | Numeric    | Amount in account   | 
| 7 | housing  | Categorical    | Does the customer have a housing loan? ("no","yes","unknown")   | 
| 8 | loan  | Categorical    | Does the customer have a personal loan? "no","yes","unknown")   | 
| 9 | contact  | Categorical    | contact communication type ("cellular","telephone")   | 
| 10 | month  | Categorical    | last contact month of year ("jan", "feb", "mar", ..., "nov", "dec")   |      
| 11 | day  | Categorical    | last contacted day  of the month   | 
| 12 | duration  | Numeric    | last contact duration, in seconds. Important note:  this attribute highly affects the output target (e.g., if duration=0 then y="no"). Yet, the duration is not known before a call is performed. Also, after the end of the call ‘y’ is obviously known   |
| 13 | campaign  | Numeric    | Number of contacts performed during this campaign and for this client includes last contact  | 
| 14 | pdays  | Numeric    | Number of days that passed by after the client was last contacted from a previous campaign (999 means client was not previously contacted)   | 
| 15 | previous  | Numeric    | number of contacts performed before this campaign and for this client   | 
| 16 | poutcome  | Categorical    | outcome of the previous marketing campaign (categorical: "failure","nonexistent","success")   |
| 17 | y  | Categorical    | has the client subscribed to a term deposit? ("yes","no")  | 

## Pipeline of Bank Marketing Analysis (EDA) :
* **Basic Exploration**
* **Checking missing values**
* **Distribution of Numerical Variables**
* **Checking Outliers**
* **Checking Skewness**
* **Feature Engineering**
* **Transformation**
* **Distribution of Categorical variables**
* **Categorial vs Numerical variables**
* **Categorical Variables vs y variable¶**
* **Campaign 1 visualisation**
* **Campaign 2 Visualisation**
* **Campaign Performance**
* **Campaign_1_failure and campaign_2_no_response**
