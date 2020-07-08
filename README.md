# Credit_Card_Default

If you didn’t pay your bills by due date, the credit card will be defaulted. While in most cases the banks can’t sell the loan, they will write it off, which is called charge off. This results in huge financial losses. Identifying which customers are most likely to default represents significant business opportunity for all banks. 

Since there is a higher cost associated with False Negative(customers who default are identified as reliable)
we choose Fbeta score as our metric where beta = 2 to weigh more on recall. 

Among 6 models(XGBoost, Gaussian Naive Bayes, Logistic, RF, LinearSVC and KNN), Gaussian Naive Bayes & Logistic have the highest Fbeta Score. Suppose I add more data, logistic will perform better since it is scalable and optimizable. In addition, it is more interpretable. So we choose logistic regression as our final model.For the corresponding confusion matrix, we can always adjust threshold based on different credit card company's lending standards. 

