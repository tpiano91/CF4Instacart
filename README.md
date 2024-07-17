# CF4_Instacart_Python_JupyterNotebooks
###### This project was completed as a requirement for the Data Analytics Program by CareerFoundry
## Project Overview
###### "You’re an analyst for an existing company, Instacart, an online grocery store that operates through an app. Instacart already has very good sales, but they want to uncover more information about their sales patterns. Your task is to perform an initial data and exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria.
###### The Instacart stakeholders are most interested in the variety of customers in their database along with their purchasing behaviors. They assume they can't target everyone using the same methods, and they’re considering a targeted marketing strategy. They want to target different customers with applicable marketing campaigns to see whether they have an effect on the sale of their products. Your analysis will inform what this strategy might look like to ensure Instacart targets the right customer profiles with the appropriate products."

## Key Questions and Objectives

##### The sales team needs to know what the busiest days of the week and hours of the day are (i.e., the days and times with the most orders) in order to schedule ads at times when there are fewer orders.
##### They also want to know whether there are particular times of the day when people spend the most money, as this might inform the type of products they advertise at these times.
##### Instacart has a lot of products with different price tags. Marketing and sales want to use simpler price range groupings to help direct their efforts.
##### Are there certain types of products that are more popular than others? The marketing and sales teams want to know which departments have the highest frequency of product orders.
##### The marketing and sales teams are particularly interested in the different types of customers in their system and how their ordering behaviors differ. For example:
###### ○ What’s the distribution among users in regards to their brand loyalty (i.e., how often do they return to Instacart)?
###### ○ Are there differences in ordering habits based on a customer’s loyalty status?
###### ○ Are there differences in ordering habits based on a customer’s region?
###### ○ Is there a connection between age and family status in terms of ordering habits?
###### ○ What different classifications does the demographic information suggest? Age? Income? Certain types of goods? Family status?
###### ○ What differences can you find in ordering habits of different customer profiles? Consider the price of orders, the frequency of orders, the products customers are ordering, and anything else you can think of.

## Insights
###### Saturdays and Sundays are the busiest days; Tuesdays and Wednesdays are the least busy
###### Frequency of orders peaks between 9AM-4PM, with the highest peak at 10AM; the hours between 9PM-6AM are by far the least busy
###### A vast majority of customers were flagged as "Middle-income"; there are a similar number of "High-income" and "Low-income" customers
###### "High-range products" (products that cost over $15) sell far fewer products than "Low-range products" (Under $5) and "Mid-range products"
###### Far more "High-income" customers, compared to "Low-income" customers bought "High-range products"
###### More "High-income" customers than "Low-income" customers classified as "loyal" or "regular" customers; more "Low-income" customers classified as "new" customers
###### "High-income" customers also account for a majority of customers who classify as "high-spenders", even more than "Middle-income" customers (despite there being twice as many "Middle-income" customers)

## Recommendations
###### Schedule advertisements during peak days/hours (weekends between 9AM-4PM) to maximize profit during these busy periods; further research needed to see how much traffic Instacart can handle during peak hours
###### Further research needed to attract customers during less busy periods
###### Only advertise "High-range" products to "high-income" customers
###### Further research needed to determine why there are comparatively few "Low-income" customers who classify as "regular" or "loyal" customers
###### Maximize potential profits off "high-income" customers/"high-spenders"; further research is needed to determine the preferred products of these groups and develop a marketing strategy to target these groups

## Folders

###### The following folders can be found in the master folder called, "Instacart Basket Analysis (no Data)"

#### 01 Project Management

###### Project Brief

#### 03 Scripts

###### All executed codes divided by task objectives

#### 04 Analysis

###### All visualizations created on Jupyter Notebooks

#### 05 Sent to Client

###### Final Excel Report

## Data

#### The dataset contains the following data tables
###### Orders
###### Orders_Products_Prior
###### Products
###### Customers
###### Departments

##### Data Source: “The Instacart Online Grocery Shopping Dataset 2017”, Accessed from Kaggle 
https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis/ on 14.11.2023

## Tools Used
###### Jupyter Notebooks
###### Libraries (pandas, numpy, os, matplotlib.pyplot, seaborn, scipy)
