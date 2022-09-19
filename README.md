# Car_price_prediction
The dataset has been collected from car dekho. It contains 13 features and 8128 rows.In this notebook,we have done preprocessing like converting the year column into number of years,
replacing categorical value with numerical value,extracting numerical value from the string column which contains both alphabets and numbers.The null values are filled 
with mean and mode.
We split the data into training and testing and scaling is done.
Four popular regression models Linear Regression, DecisionTreeRegressor, Lasso Regression, RandomForestRegressor, are implemented to evaluate the performance of the model 
for predicting the selling price of the car.
RandomForestRegressor outperforms all the models and we obtained the highest model score as 95%.
