# Appliance-Energy-Prediction
## Project Type - Regression

### PROBLEM STATEMENT
In this project we have given some feature which affect the energy consumption , we have to analyse which factor affecting the most and prediction of energy consumption by knowing the features.

### Project Summary

- In this project we are going to predict the energy usage of appliance.The data that we have been provided has a data set is of 10 min for about 4.5 months.Data has been made up by monitoring House temprature and Humidity condition by a Zigbee wireless sensor network.Each wireless node transmitted the temprature and Humidity condition for 3.3 minute and the wirelss Data was averaged for 10 minutes.The energy data was logged every 10 minutes with m-bus energy metres. Weather from the nearest airport station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis(rp5.ru) and merged together with experimental data set using Date and time coloumn.In this Data set there are two variables that has been included for testing the regression models and to filter out non- predictive attributes.
### Data finding

- There are no missing values in the data as wells no duplicate values.From the data we get to know that there are 29 coloumn of which 26 are of float type,2 are of integer type and only one is of object type.

### Data Wrangling
![image](https://github.com/KapilNarayanSingh/Appliance-Energy-Prediction/assets/117643744/4291ca72-d6a8-4920-a535-7b28325736fc)

### Deploying different models on the data and evaluating the best model for the dataset.

1	 Lasso

2	Ridge

3	ElasticNet

4	DecisionTreeRegressor

5	KNeighborsRegressor

6	SVR

7	RandomForest

8	GradientBoostingRegressor

9	XGBRegressor

10	AdaBoostRegressor

### CONCLUSION
- We have done eda analysis of the data set and come to various conclusion.
- After that we removed the outliers and its affect.
- At last we implemented various algorithm and come to conclusion that Random forest regressor is the best algorithm.
- Then we have done hyperparameter tuning using grid search cross validation technique and evaluated Random forest regressor result.
