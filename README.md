# Bank-Customer-Churn
Predicting the customer churn on a Bank's historical customer data

The best fit model here we get was Random Forest with best accuracy and F1 score upon solving the class imbalance in our data.

In order to make the model better, we can use "RandomizedResearchCV" method to be precise and to fine tune the parameters, and could have used the cross-validation method to avoid the contingency of the results.
Once we obtain the best model, we initiate the model with these parameters and calculate the score of accuracy using cross validation.
Also, we can focus more on feature engineering.
In these experiments above, we used all features for modelling, but in fact we can discard the features with the lowest contribution one by one to improve the model performance until the model performance converges. We found that there are some features whose data have large differences, for example, the columns- Balance, Estimated Salary and Tenure, so we need to standardize them.
