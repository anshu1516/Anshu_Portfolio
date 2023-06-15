# Anshu_Portfolio
Data Analyst Portfolio
# [Project 1: Payment Date Prediction: Project Overview](https://github.com/anshu1516/Anshu_Portfolio/blob/main/Payment%20date%20prediction.ipynb)
1. Understood the dataset and meaning of the terms used in columns and identified the problem.
2. Learned some basic machine learning steps and techniques to wrangle the problem.
3. Reason for splitting on a date basis:- Since in some of the use cases we will always be making predictions for the future data, we will have to make the train, validation, and test split based on a date instead of a random split. For example, if we are training the model for data between January and September, the validation set can be from October to mid of November and the test set from mid of November and onwards.
4. Learned some basic machine learning algorithms like linear regression and decision tree and increased the model efficiency by 28%.
5. Machine Learning Model to predict the payment date of an invoice when it gets created in the system.
6. Categorize the invoice into different buckets based on the predicted payment date.

The invoices dataset contains the past payment information and behaviour of various buyers. Based on the previous payment patterns, the ML model will predict what will be the date a payment is made by the customer for an invoice.
The model will also predict which aging bucket the invoice falls into based on the predicted payment date.
The different buckets will be :
 0-15 days
 16-30 days
 31-45 days
 46-60 days
 Greater than 60 days


 
# [Project 2: Price Prediction: Project Overview](https://github.com/anshu1516/Anshu_Portfolio/blob/main/Price%20prediction.ipynb)
We have 2 datasets here — training set and test set.

The training set contains the features, along with the prices of the flights. It contains 10683 records, 10 input features and 1 output column — ‘Price’.

The test set contains 2671 records and 10 input features. The output ‘Price’ column needs to be predicted in this set. We will use Regression techniques here, since the predicted output will be a continuous value.

Following is the features available in the dataset – Airline, Date_of_Journey, Source, Destination, Route, Dep_Time, Arrival_Time ,Duration, Total_Stops, Additional_Info, Price.

I will start by importing all the necessary libraries that we need for this task and import the train dataset.
 1. Importing Libraries
 2. Importing the dataset
In Data Analysis We will try to Find out the below stuff
 1. Missing Values in the dataset.
 2. All the Numerical variables and Distribution of the numerical variables
 3. Categorical Variables
 4. Outliers
 5. Relationship between an independent and dependent feature(price)

Handling Categorical Data
 1. Nominal data→ data are not in any order → OneHotEncoder is used in this case
 2. Ordinal data → data are in order → LabelEncoder is used in this case.
