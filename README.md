# EDA-Telecom-Churn-Analysis

# Introduction
The telecommunications business is growing quickly, and service providers are more focused on growing their subscriber bases. Retaining current clients has become one of the biggest challenges in order to meet the demand of surviving in the competitive industry. According to a survey conducted in the telecom sector, gaining a new client costs significantly more than keeping an existing one.It is therefore possible to forecast whether or not customers would leave a company by gathering knowledge from the telecom industry. The telecom sectors must take the necessary steps to start acquiring their related clients in order to prevent their market value from stagnating.

# Problem Statement
Orange S.A., formerly France Télécom S.A., is a French multinational telecommunications corporation. The Orange Telecom's Churn Dataset, consists of cleaned customer activity data (features), along with a churn label specifying whether a customer canceled the subscription. In this problem statement we were required to explore and analyze the data to discover key factors responsible for customer churn and come up with ways/recommendations to ensure customer retention.

# Dataset Information

Dataset has 20 features, of which 19 are predictor variables and ons is Target variable.

Variables Description:

State: Describes the state of the telecom account. There are 51 states in total.

Account Length: From how long the account is active.

Area Code: Describes which states are under in which Area code. There are a total of 3 Area codes.

lnternational Plan: How many accounts are having International plan(yes,no)

Voicemail Plan: How many accounts are having Voice Mail plan subscription-(yes,no)

Voicemail Message: No.of voice mail messages have been sent in the given time.

Total Day Minutes: Total number of day minutes talked in a day.

Total Day calls: Total Number of calls made in a day.

Total Day Charge: Cost per Total Number of calls made in a day.

Total Eve Mins: Total number of minutes talked in Evening.

Total Eve Calls: Total evening calls made in the Evening.

Total Eve Charge: Cost per Total Number of calls made in Evening.

Total Night Mins: Total number of minutes talked in the Night.

Total Night Calls: Total Number of calls made in Night.

Night Charge: Cost per Total Number of calls made in night.

International Minutes: Total number of minutes used.

International Calls: Total number of International calls made

International Charge: Cost per Total Number of International calls used. International

Customer Service calls: Number of customer service calls made.

Churn: Customer who are churned/retained (Target Variable True, False).



# Solutions to Reduce Customer Churn

•International Plan has to be modified as the call charge is same as the customers with no Internatinal plan.
•Customer service to be modified by rectifying the complaints/promblems raised by customers effictively. And, Feedbacks has to taken time to time.
•Look at the customers facing problem in the most churning states.
•Resove Poor Network Connectivity Issue in the states with higher churning rate.
•Run predictive analysis on the customers, promote new offers to customers who are likely to churn.
•Stay competitive and adopt the latest technolgies for attracting the new customers as well as retaing the existing customers.

# Conclusion

• Customers with the International plan have higher churn rate.

• Customers who made service calls above four are churning at percentage beyond 50%, whereas service calls less than 4 are around 10%.

• Customers who have higher Day call minutes, Evening call minutes, Night minutes are having higher churn number.

• Customers with Account length ranges from 75-130 are churning heavily.

• There is no clear association of churn with the variables Area code, Day calls, Evening calls, Night calls, International calls and Voicemail messages.
