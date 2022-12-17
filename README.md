# Store_Purchases_Analysis_Using_Python

## Project Overview
In this project, we use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

## Following steps were followed for analysis and visualisation:

### 1.Understanding the dataset  
The dataset contains name of the products along with their order IDs and how many products were purchased along with their purchases date and much more.

### 2.Data cleaning
Tasks during this section include:  
* Drop NaN values from DataFrame.  
* Removing rows based on a condition.  
* Change the type of columns (to_numeric, to_datetime, astype).  

### 3.Data exploration
In this section we explore insightful business questions related to our data set and those are as follows:

* What was the best month for sales? How much was earned that month?  
* What city sold the most product?  
* What time should we display advertisemens to maximize the likelihood of customer’s buying product?  
* What products are most often sold together?  
* What product sold the most? Why do you think it sold the most?  

### 4.To answer these questions we walk through many different pandas & matplotlib methods. They include:

* Concatenating multiple csvs together to create a new DataFrame (pd.concat)
* Adding columns
* Parsing cells as strings to make new columns (.str)
* Using the .apply() method
* Using groupby to perform aggregate analysis
* Plotting bar charts and lines graphs to visualize our results
* Labeling our graphs
