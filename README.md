#Overview:
-In this project we have a customer dataset where we analyze retention and churning of customers ,and possible reasons for them not returning compared to those that did not leave the business.We do this through Explortory Data Analysis and visualizations in python to gain these insights

#STEPS
1.Importing Libraries
-Tools:Using Pandas to import data,matplotlib and seaborn for data visualizations


2.Loading the dataset
-Loaded  the dataset into pandas datafrme:Telco-Customer-Churn dataset ,the dataset source was from kaggle where Each row represents a customer, with each coloumn containing the customers’ attributes

3.Exploring the Data Set 
-I did a overview of the dataset getting the information such as row numbers and the number of coloumns(shape), number of of null values on each coloumn,and the datatypes of each coloumn

4.Exploratory Data Analysis in Context Of the Data and Making Visualizations

-Getting the amount of customers the company could not retain compared to how many were retained

-looking at how the type of contract affect customers ,whether they leave or the business retains them based on their type of contract
-trying to understand how pricing affects customer retention and churning
-getting the average prices for the people that left and the people that stayed(month-to-month since most people leaving are in the mTm bracket,this also prevents outliers)
-plotting the effect of charges
-seeing which payment method most people are using

5Conclusion an Making Insights and Understanding the data
-Many customers with the month-to-monh subscription left,more with a longer subcription were retained, therforefore is it better to promote year long subscription...?
-AverageMonthlyCharges were higher for the custumers that left than those who remained
-Other insights we saw how people mostly prefer to use Electronic payments than the rest (both curned and retained customers)
-Using a histogram and looking atth distribution of payments made by use on month to month contracts,the distibution was skewed to the right,showing that many user might prefer lower prices/payments
