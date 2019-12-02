# Prediction Model to compute customer health score
Build Date :21 September 2019
Build Author : Shivendra Singh

# Description
It is very relevant for a firm to understand the issues their customers are facing. One major component includes idenifying the customers whicha are unhappy and might leave the company in the current or next financial year. Many strategies can be implemented to save these customers. I becomes evena bigger issue when the customer base being  targeted is very niche such as Senior Management of Companies.The data present in our case is provided by CEO training firm.

# Objective 

In this project, I have worked on predicting the probability of a customer churning in the upcoming financial year based on the data provided for each consumer for the past 5 years . Most of the data provided was static in nature i.e. Age, Subscription Tenure and other profile related information.The dynamic features provided were attendance to group classes and yearly revenue generated from each member. Using these informations,  a number of features were engineered to be used for creating a prediction model with an accuracy of __81%__. 

# Methodology
1. __Data exploration__ :
  a.  Clean member attributes to treat the missing responses and inconsistencies
  b.  Remove correlated variables from the dataset

2. __Data processing__ :
  a.  Generate new features such as annual revenue change, annual group input/output etc. to improve accuracy

3. __Model Development__ :
  a.  Create Models – Logistic Regression, Random Forest and Gradient Boosting
  b.  Select best model to obtain optimized results – based on AUC/ROC metric
  
4. __Model Validation__ :
  a.  Validate model using AUC-ROC curve
  b.  Compute health score for all active members

# Conclusion
Initially, logistic regression model was trained to obtain a accuracy (ROC-AUC) of ~67% after parameter tuning. The best model obtained after comparison was Gradient Boosting Method.It provided an accuracy of __81%__. __68%__ of the customers tagged as "High risk to churn" by the model actually left the company in the next year hence validating the accuracy of the model.
