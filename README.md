# Credit_Card_Default

If you didn’t pay your bills by due date, the credit card will be defaulted. While in most cases the banks can’t sell the loan, they will write it off, which is called charge off. This results in huge financial losses. Identifying which customers are most likely to default represents significant business opportunity for all banks. 

Since there is a higher cost associated with False Negative(customers who default are identified as reliable)
we choose beta = 2 to weigh more on recall. 

Among 6 models(XGBoost, Gaussian Naive Bayes, Logistic, RF, LinearSVC and KNN), Considering if I add more data, logistic will perform better since it is scalable and optimizable. In addition, it is more interpretable. We can always adjust threshold based on different credit card company's lending standards. If it has tighter charge off rate we can increase the threshold to decrease False Negative and vice versa. 


