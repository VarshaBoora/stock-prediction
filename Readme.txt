
Team Information :
------------------
Lionel lobo - 001342786
Varsha Boora - 001055347

DataSet Names:
--------------
1)amazon_stock_prices_sample
2)wallmart_stock_prices_sample
3)uber_stock_prices_sample

Description:
-------------
"stock_prices_sample" contains the following fields:
"Date"- Records of stock from 19-1-2017 to 17-1-2020
"Opening"- Opening price which ranges from 800$ to 2000$ 
"High"- Highest values of stock
"Low"- Lowest value of stock 
"Close"- The value at which the stock has been closed
"Adj_Close"- Adjusted Closing price factors in anything that might affect the stock price after the market closes
"Volume"- Volume is the number of shares or contracts traded in a security or an entire market during a given period of time


Amazon_stock_prices.ipynb:
Can predict amazon stock for 282 days ahead using Random forest algorithm with an accuracy of 00.7083274175218012

Steps for prediction:
1)Import the Pandas library and read the "amazon_stock_prices_sample.csv" file
2)View first five rows
3)Import Random Forest and Scikit-learn modules 
4)Check Columns
5)Shifting close down to predict next day
6)Remove NA and applying regression while trying to predict close from non Close columns, Getting the trainig sets X_train   
7) Creating and traing the model
8) Find R2 measure(accuracy)
9)Model prediction 
10)import matplotlib to plot predictions
11)Plot predictions on top of test labels to see if we have a match

Wallmart_stock_prices.ipynb:
Can predict amazon stock for 61 days ahead using Random forest algorithm with an accuracy of 0.7023792410525198
1)Import the Pandas library and read the "wallmart_stock_prices_sample.csv" file
2)View first five rows
3)Import Random Forest and Scikit-learn modules 
4)Check Columns
5)Shifting close down to predict next day
6)Remove NA and applying regression while trying to predict close from non Close columns, Getting the trainig sets X_train   
7) Creating and traing the model
8) Find R2 measure(accuracy)
9)Model prediction 
10)import matplotlib to plot predictions
11)Plot predictions on top of test labels to see if we have a match


Uber_stock_prices.ipynb:
Can predict amazon stock for 20 days ahead using Random forest algorithm with an accuracy of 0.7246882817691083
1)Import the Pandas library and read the "uber_stock_prices_sample.csv" file
2)View first five rows
3)Import Random Forest and Scikit-learn modules 
4)Check Columns
5)Shifting close down to predict next day
6)Remove NA and applying regression while trying to predict close from non Close columns, Getting the trainig sets X_train   
7) Creating and traing the model
8) Find R2 measure(accuracy)
9)Model prediction 
10)import matplotlib to plot predictions
11)Plot predictions on top of test labels to see if we have a match



