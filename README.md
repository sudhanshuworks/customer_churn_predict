# **Churn Classification Project**

Retention of users is very important in companies, websites or telecommunication companies. Involving potential customers in our company,
attracting customers who are considering leaving, or identifying customers that we cannot keep no matter what we do and not investing more will return
us positive in terms of efficiency.For these reasons, churn analysis allows us to take action in advance and improve our marketing and investment techniques
in this direction.

# **Required Libraries**
*pandas (load and manipulate data and for One-Hot Encoding)

*numpy (calculate the mean and standard deviation)

*seaborn (some graphs)

*sklearn.model_selection , train_test_split (split data into training and testing sets)

*sklearn.model_selection , GridSearchCV (cross validation)

*sklearn.metrics , confusion_matrix (creates a confusion matrix)

*sklearn.metrics , plot_confusion_matrix (draws a confusion matrix)

*matplotlib.pyplot

# **About Dataset**

##The data contains information about almost 6000 users, their demographic characteristics, the services they use, the duration of using the operator's services, the method of payment, and the amount of payment. Features are showing below.

*customerID - customer id

*gender - client gender (male / female)

*SeniorCitizen - is the client retired (1, 0)

*Partner - is the client married (Yes, No)

*tenure - how many months a person has been a client of the company

*PhoneService - is the telephone service connected (Yes, No)

*MultipleLines - are multiple phone lines connected (Yes, No, No phone service)

*InternetService - client's Internet service provider (DSL, Fiber optic, No)

*OnlineSecurity - is the online security service connected (Yes, No, No internet service)

*OnlineBackup - is the online backup service activated (Yes, No, No internet service)

*DeviceProtection - does the client have equipment insurance (Yes, No, No internet service)

*TechSupport - is the technical support service connected (Yes, No, No internet service)

*StreamingTV - is the streaming TV service connected (Yes, No, No internet service)

*StreamingMovies - is the streaming cinema service activated (Yes, No, No internet service)

*Contract - type of customer contract (Month-to-month, One year, Two year)

*PaperlessBilling - whether the client uses paperless billing (Yes, No)

*PaymentMethod - payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))

*MonthlyCharges - current monthly payment

*TotalCharges - the total amount that the client paid for the services for the entire time

*Churn - whether there was a churn (Yes or No)
