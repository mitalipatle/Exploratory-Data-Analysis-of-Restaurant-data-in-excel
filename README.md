# Restaurant-data-analysis-in-excel

## Introduction:

Being a major food enthusiast and a food and beverage server in one of the restaurants in Ireland, I am accustomed to receiving regular meal orders from patrons. This raises a lot of questions in my mind regarding the restaurant's business. I came upon a nice dataset about restaurants and orders and what would have deterred a data geek from exploring it on the route to this search. This project is an example of how my data science expertise and passion in the topic come together in a simple yet intriguing way. I was able to use Excel to its fullest extent thanks to this assignment, and the insights I gained from it have provided many answers.



## Scope:

##### 1). Data Cleaning and formatting.
##### 2). Administered functions like IFs, VLOOKUPS to projects information on restauarants,cuisines along with final sales by restauarnts after discount.
##### 3). Utilisation of pivot tables to summarize information and answering to important questions through visualisation.

## Data Used:
The data used in the project is taken from kaggle which consists of two tables that carries information on restaurants and orders. The orders and restaurants dataset represents 500 rows, 10 columns and 20 rows,5 columns respectively. 

## Data cleaning and formatting:
To make it simple to sort, filter, and format data, the orders dataset is first transformed into a table. The dataset was examined for the existence of blank cells and null values in order to clean it up. The columns were then given proper names, and any unnecessary columns were removed. The columns received the correct data formatting and had any duplicate values checked.

## Function Utilisation:
Every consumer who placed an order for food worth ₹500 or more is entitled to a 5% discount. In order to identify those who are qualified for a discount, the IF function is used in conjunction with the column to construct a column with a discount.

<img src="https://github.com/mitalipatle/Restaurant-data-analysis-in-excel/blob/main/Images/discounted%20price.png">

Similar to this, the VLOOKUP function is used to find the values from the restaurant table using the restaurant id as a reference in order to include restaurant names and cuisines served by them in the orders table.

<img src="https://github.com/mitalipatle/Restaurant-data-analysis-in-excel/blob/main/Images/ADDING%20CUISINE%20IN%20ORDER%20USING%20VLOOKUP.png">
