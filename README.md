# defaulter_payment_analysis
The bank performs a charge-off on delinquent credit cards and eats the losses. If only there was a way to predict which customers had the highest probability of defaulting so it may be prevented…
Problem
Can we reliably predict who has is likely to default? If so, the bank may be able to prevent the loss by providing the customer with alternative options (such as forbearance or debt consolidation, etc.). I will use various machine learning classification techniques to perform my analysis.
Data

Target: Did the customer default? (Yes=1/Positive, No=0/Negative)
Features:
1.Credit Limit: Amount of the given credit (in dollars): it includes both the individual consumer credit and his/her family (supplementary) credit
2.Sex (1=male; 2=female)
3.Education (1=graduate school; 2=university; 3=high school; 4=other)
4.Marital Status (1=married; 2=single; 3=others)
5.Age (years)
6.History of past payment: The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above
7.Amount of bill statement (dollars) for past 6 months
   

# Methodology
1.Exploratory Data Analysis
2.Baseline Model
3.Performance Metrics
4.Optimization
5.Feature Importance
6.Hyperparameter Tuning
7.Class Imbalance
8.Analyze Results
