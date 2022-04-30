# Starbucks-Caspstone-Project

## Getting Started
This is a capstone project of the Udacity Data Science Nanodegree program. This project uses data from the starbucks rewards program to determine
customer demographic groups who respond best to the different offer types. A machine learning model was also built to determine whether a customer will successfully 
complete an offer.

## Installations
* Python 3.8
* NumPy
* Pandas
* Seaborn
* Matplotlib
* Scikit-Learn Libraries: LogisticRegression, RandomForestClassifier, GradientBoostingClassifier and other Scikit-Learn components
* pickle

## Project Overview
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, 
Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer 
such as a discount or BOGO (buy one get one free).
Some users might not receive any offer during certain weeks.
Not all users receive the same offer, and that was the challenge to solve with this data set.
The task involved combining transaction, demographic and offer data to determine which demographic groups responded best to which offer type. 

Every offer has a validity period before the offer expires. As an example, a BOGO offer might be valid for only 5 days. 

Here, informational offers have a validity period even though these ads are merely providing information about a product;
for example, if an informational offer has 7 days of validity, we can assume the customer is feeling the influence of the offer for 7 days after receiving the advertisement.

Transactional data showing user purchases made on the app including the timestamp of purchase and the amount of money spent on a purchase was also provided.
This transactional data has a record for each offer that a user receives as well as a record for when a user actually views the offer. 
There are also records for when a user completes an offer.

Keep in mind as well that someone using the app might make a purchase through the app without having received an offer or seen an offer.

## Project Motivation
* As a customer serving business, it's important to be effective in sending out offers. Are you sending offers to customers who are more likely to complete them?
How can you measure this ? With this project, two techniques were used; an analytical study of available data to determine customers who completed the different
offers and a machine learning model to determine whether a customer will complete an offer.
* Here's the link to my Medium post: 

## File Description
* Data : contains the three datasets
* Models: contains the trained models used in this project
* Notebook: contains the python code used to execute this project

# Summary 
* Customers that earned between $60,000 and $80,000 completed more offers than other income groups. 
* Customers between 40 and 60 years old completed more offers than other age groups.
* Customers who spent less than 200 dollars since joining the program completed more offers than the other customers. 
* The total amount a customer spends is the important feature in predicting whether a customer will successfully complete an offer. 
* Offer characteristics like reward, difficulty and duration are important in predicting whether a customer completes an offer. The customer's income and membership year are also key features.

# Licesning and Acknowledgement
This project was completed by me as part of the requirements for the Udacity Data Science Nanodegree. The original data was provided by Starbucks for Udacity.
