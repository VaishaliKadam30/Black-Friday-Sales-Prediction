# Black-Friday-Sales-Prediction
What is Black Friday?
It is an unofficial holiday in many states in the US and a major day for both shoppers and sellers. With Christmas just a month later, Black Friday serves as an opportunity for customers to do their Christmas shopping while retailers also try to drive up their profits by generating more sales.

Black Friday has become one of the main shopping days for people around the world due to the wide variety of discounts and offers it offers. The Black Friday sales also give shoppers the opportunity to take advantage of limited-time deals and find the best ones available.

Black Friday is a colloquial term for the Friday after Thanksgiving in the United States. It traditionally marks the start of the Christmas shopping season in the United States. Many stores offer highly promoted sales at discounted prices and often open early, sometimes as early as midnight or even on Thanksgiving.

Features Information :

Variable Definition

● User_ID : User ID
● Product_ID : Product ID
● Gender : Sex of User
● Age : Age in bins
Proprietary content. ©Fireblaze AI School. All Rights Reserved. Unauthorized use or
distribution prohibited
● Occupation : Occupation(Masked)
● City_Category : Category of the City (A,B,C)
● StayInCurrentCity Years : Number of years stay in current city
● Marital_Status : Marital Status
● ProductCategory1 : Product Category (Masked)
● ProductCategory2: Product may belongs to other category
also (Masked)
● ProductCategory3 : Product may belongs to other category
also (Masked)
● Purchase : Purchase Amount (Target Variable)

Problem Statement
A retail company “ABC Private Limited” wants to understand the customer purchase behavior (specifically, purchase amount) against various products of different categories. They have shared purchase summaries of various customers for selected high-volume products from last month. The data set also contains customer demographics (age, gender, marital status, city type, stayincurrentcity), product details (productid and product category), and Total purchase amount from last month.

Now, they want to build a model to predict the purchase amount of customers against various products which will help them to create a personalized offer for customers against different products.

The points should be considered is :
1.Purchase distribution(targeted variable)pattern
2.Checking of Outliers
3.EDA:-Analysis by Gender, Marital Status, occupation,City,ProductId,UserId,Age,Stayincurrentcity,ProductCategory1/2/3 with respect to the purchase.
4.DataPreprocessing
5.Building of Model and Calculate the Accuracy Score of the train and test model

Accuracy of train and test
Linear Regression
The Root mean squared error of Linear Regression Model  Train model is: 4699.890666730313 
The Root mean squared error Linear Regression Model Test model is: 4700.968134811108 
DecisionTreeRegressor
R2 score :- The accuracy is 64%
Random Forest Regressor
Training Model Accuracy is 69%
Testing Accuracy is 66%
XGBoost Regressor
Training Model Accuracy score is 63.97 %
Testing Model Accuracy score is 62.91 % 
This is good model


Solution:-
If we want to increase the sale we have good accuracy model but for increase the selling product:-
        1.Those product which sell more we have to full the stock of that product so has to easily avaiable to customer.
        2.Those product which is large stock we put it in a discount so has to attract the consumer
        3.Mainly 26-35 age group people purchase more that may be family so we put scheme in different products.
        4.People bore in one to two year their purchasing is low after some time so as we put variety of product that they 
        don't go here and there.
        5.The customer which is frequent i.e regular we give them some gift /voucher so as to attract other customer
        6.In staycityyear column we can observe that the people purchase more that may be they just shift to that city so 
        to attract them we basically focus what product they purchase more for them..
        7.We just focus on the purchase distribution pattern to figure out what product is purchased by whom and make them     available
        
Thank You

