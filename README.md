# SBER_BANK_HOUSE_PRICE_FROM_KAGGLE
The aim of this SBER bank is to predict the price of the property or buildings in Russia. Which helps its customers,developers and lenders to invest into it confidently. Predictions of price are not solely dependent on locality, area, material used , built in area , number of living rooms and number of floors in a building and ; which is related to the metadata of that property. But, also it depends on the russsian economy which is very unstable. This macroeconomic of the country dataset consist of huge set of features such as GDP and its growth , employment rate, birth rate, death rate, average salary growth rate , male to female ratio, ecology type , average retail share per capita in this way it consists of country feature dataset. In addition, this dataset also consists of complete data about the neighbours near by area. The KPI we using here is RMSLE - root mean square log error i.e log of root mean square error which is not affected to outliers and also penalize the underestimation of the price heavily.

**Type of Machine Learning Problem:-
We are predicting house prices based on the the locality and country finance so it is a regression Problem.

**Performance metric :-
This is regression problem we can use Mean square error, Mean Absolute error, Median Absolute error, R Squared (R2), this all can be used but RMSLE (Root Mean Squared Logarithmic Error) is used. In the case of RMSE or MSE the presence of outliers can explode the error term to a very high value. But, in the case of RMSLE the outliers are drastically scaled down because of log which nullify the outlier effect on the model. SO RMSLE is used . we may get doubt MAD can be used but MAD nullify the error greatly compare to mean absolute deviation. Here RMSLE could be a great fit can be used when you don’t want to penalize huge differences when both the values are huge numbers.Also, this can be used when you want to penalize under estimates more than over estimates.


**Description of each feature in the data set
Data set column analysis



## there are many features in this data set which needs rigorous EDA to get the insight of this data.
