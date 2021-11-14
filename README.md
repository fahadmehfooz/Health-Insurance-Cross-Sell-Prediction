# Health Insurance Cross Sell Prediction: Project Overview

## Problem Statement: 

* We have an insurance company as our client that has provided Health Insurance to its customers. Now they want a model to predict whether the policyholders from last year will be interested in Vehicle Insurance provided by the company. Such a model will be extremely helpful to the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.
* We have been provided with information of customers of the company broadly on following categories:

* Demographics  -  Gender, Age, Region Code Type
* Vehicles -  Vehicle Age and Damage
* Policy - Annual Premium, Previously Insured Status and Sourcing Channel

## Data Acquisition:
* The first step in the pipeline aims at importing our dataset into our environment. In our case; we will import the dataset provided by the insurance company.

### EXPLORATORY DATA ANALYSIS:

* We observe that we have 381109 entries in our dataset and none of the columns contain any null values.
* Further it is also checked that there are no duplicate rows in our dataset which means that we have data on 381109 unique customers.
* Each column has all its entries of the same type as described by the column itself which means that there are no miscellaneous data in any column.
* Now let us take a look at the description of the numerical columns which consist of ‘Age’ , ‘Annual Premium’ and ‘Vintage’.

##   DATA CLEANING
*  On analyzing the numerical columns in our dataset namely ‘Age’, ‘Annual Premium’ and    ‘Vintage’ ; we observe that only Annual Premium consists of outliers.
* Applying log transformation to ‘Annual Premium’ column handles the outliers and also in addition gives a normal distribution of the data.


