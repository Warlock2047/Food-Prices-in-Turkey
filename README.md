# Food Prices in Turkey
1. Place: Where the data comes from
2. ProductId: Id of the food product 
3. ProductName: Name of the food product 
4. UmId: Unified omni-ID 
5. UmName: Compound omni-name
6. Month: The month the data was collected 
7. Year: The year the data was collected 
8. Price: The price of the food product

There are two data sets in the data, test and train:
Train data includes data collected prior to Covid-19. Test data includes data collected after Covid-19.

# REPORT
1. We observed the frequency of the variables to be included in the analysis according to the count. We get information about the distributions of the variables in the data, we observed that the Price variable is skewed to the right.
2. We examined that the distribution of the researched data in the locations was more or less in which province according to the years.
3. We analyzed the distribution of food prices by years by making a pie chart. We have seen that there are more in 2019 and 2018.

# MODELING
- Since the R-squared value is 0.92 in our Linear Regression Model, our model is 92% significant.
- We created multiple linear regression model using our three variables. Since the R-squared value is 0.93, our model is 93% significant.
- As a result, when we look at the RMSE and Rsquared values of the two models, we see that the model we should choose is our second one, the Multiple Linear Regression Model.

- [Data Set](https://www.kaggle.com/datasets/leventoz/food-prices-in-turkey)
