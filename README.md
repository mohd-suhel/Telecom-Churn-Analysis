# Telecom-Churn-Analysis
Detecting customers who are likely to cancel a subscription to a Telecom service
In this project, the goal is to identify churn customers, that is, customers most likely to cancel subscription to a fictitious telecom company. Customer churn is a really interesting problem, because once identified, it is possible to focus on retention actions, providing adequate intervention to encourage them to stay and minimize customer exit. The dataset for this project was obtained from the OpenML public repository. The dataset relating features of account and usage for churn and non churn clients. In the context of this project, this is a problem of supervised classification and Machine Learning algorithms will be used for the development of predictive models and evaluation of accuracy and performance. It seeks to find the most appropriate model for the business.

# 1. Churn
Churn Customer can be defined as a user who is likely to discontinue using the services. So, the target variable confirm if the customer has churned (1=yes; 0 = no).

# 2. Dataset
The data included 5.000 users and by the exploratory analysis, it is observed that:

14% of the base are classified as churn.
50% of the customers who called the company more than 3 times are classified as Churn.
10% of those with no international plan are classified as Churn x 8% of those with an international plan are Churn.
## 2.1 Columns
 'ID'
'area_code'
'state'
'account_length'
'international_plan'
'voice_mail_plan'
'number_vmail_messages'
'total_day_minutes'
'total_day_calls'
'total_day_charge'
'total_eve_minutes'
'total_eve_calls'
'total_eve_charge'
'total_night_minutes'
'total_night_calls'
'total_night_charge'
'total_intl_minutes'
'total_intl_calls'
'total_intl_charge'
'number_customer_service_calls'
Target

'class'
# 3. Features Importance
According to the feature importance analysis the following feature are important:

1. total_minutes(day,eve,night,intl)
2. total_charge(day,eve,night,intl)
3. number_customer_service_calls
4. total_eve_minutes
5. international_plan   
6. State
7. Area Code

# 4. Tools
Jupyter notebook, Python 3.5.2 (Pandas, Numpy, Matplotlib and Seaborn)
