# Debt-Prediction

A.Read the dataset file “Credit.csv” (from github using the following command), and assign it to a Pandas DataFrame:

B.Check out the dataset. The “Credit” dataset includes the “balance” column (average credit card debt for a number of individuals) as target, as well as several features: age, cards (number of credit cards), education (years of education), income (in thousands of dollars), limit (credit limit), marital status, and rating (credit rating).

C.Generate the feature matrix and target vector (target is “balance” in this dataset). Then, normalize (scale) the features (note: don’t normalize the target vector!). To normalize the data, you can simply use scale(X) from sklearn.

D.Split the dataset into testing and training sets with the following parameters: test_size=0.24, random_state=4.

E.Use Linear Regression to train a linear model on the training set. Check the coefficients of the linear regression model. Which feature is the most important? Which feature is the least important?

F.Predict “balance” for the users in testing set. Then, compare the predicted balance with the actual balance by calculating and reporting the RMSE (as we saw in lab tutorial 4).

G.Now, use 10-fold Cross-Validation to evaluate the performance of a linear regression in predicting the balance. Thus, rather than splitting the dataset into testing and training, use Cross-Validation to evaluate the regression performance. What is the RMSE when you use cross validation?
