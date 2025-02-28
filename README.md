Identify incredible customers based on their financial transactions and debt classification group.

As part of the requirements, you as a data analyst have to decide “Which group of debts are incredible”, as long as it helps to distinguish between credible and incredible customers (Data Timeframe: Mar to Jun 2021)

Several comments and initial guess: 
-  Customers with high transaction values seem to have a higher tendency to be in the credible groups.
-  Monthly average amount seems to be a good predictor for debt group classification

In this project, I used two ML models (Logistic Regression and kNN) to classify incredible/credible debt groups built on categorical dummy variables (customer age, gender, marital status, transaction type, term deposit type) and numerical features (monthly average transaction value, min & max transaction value from Mar to June 2021, average amount by debt group, change in amount for 3 months vs. for 1 month, account balance) and 1 outcome variable (debt group from group 1 to 5)

The result indicated that kNN model performed better due to higher accuracy score and F1 score as compared to Logistic Regression's.
