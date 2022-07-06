# Car-Price-Predictor
An API based model to predict the price of an used vehicle
This model uses Linear Reggression and Lasso Regression to detrermine the Selling Price of an used Automobile.
The error factor is calculated by the R squared method.
Although we used Linear Regression to get a close result, The Lasso regression model gave us a better result.
We used pandas Library to import and read the csv file from the folder. We checked the content of the first 5 rows of the csv file and also got the total number of rows and columns on the csv file. Then confirmed that their is no missing value in the data.
Since a computer cant read text, we changed the categorical data to numerical values like 0,1,2.
After that, we split the data into Target data. Since we dont need the car name and actual selling price, we got rid of that.
We also stored the actual selling price in another variable.
After that, we split about 10% of the data into testing data and the rest to training data.
Then the model training began. First we trained the model using Linear Regression and then with Lasso Regression.
We saw each plot after the model got trained. 
We found that the model trained with lasso regression worked better and gave less error.
