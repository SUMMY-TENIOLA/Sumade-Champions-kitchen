# SUMADE-CHAMPIONS-KITCHEN REPORT

A business owner wants to know which item is the least profitable or the most profitable at the conclusion of every calendar year by comparing sales and profit from one year to the next. The goal of the project is to examine store sales numbers from 2013 and 2014 and make suggestions for how to make them better the following year.

ABOUT THE DATASET

The information might be found at @kaggle.com and https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download. The information includes a row, an order id, an order date, an order ship date, a ship mode, a customer id, a customer name, segment, a nation, a city, a state, a postal code, a region, a product id, a catergory, a sub-category, a product name, sales, a city, a quantity, a discount, and a profit.

![image](https://user-images.githubusercontent.com/119289961/224686870-fec992a8-6dda-4457-ab64-49b21799ac8f.png)  
Rawdata

The tool used: Power BI, Excel, and PowerPoint were the tools used.
I cleaned my Excel dataset.
• I eliminated all duplicate data; I added a table; and I added five additional columns to the dataset: Month number, Month name, Year, continent, and category.
• I used a conditional statement to look for the category and continent, and I used a year, month, and text statement to look for the name and number of the month, and a year respectively

![image](https://user-images.githubusercontent.com/119289961/224688431-bf1ea42f-fbac-42a7-beb9-2c0b803b4c45.png)  
Cleaned data

The values were categorized into the dimension table and fact table after importing the dataset into the power query.
• The fact table is a table that includes duplicates, foreign keys, continuous variables, dates, and quantitative data of all forms.
• The dimension table has no duplicates, text data of the text data type, categorical variables, and primary keys.
The fact table (primary key) was linked to all dimension tables (foreign keys), creating linkages between all of the tables. In order to link all relevant data and produce zero-error visualizations, this is done.

![image](https://user-images.githubusercontent.com/119289961/224690306-8d4e01bb-2d58-43c3-9b44-a2cc0d27d6c9.png)  
Data Model

DATA CLEANING PROCESS 

I made a new measure named Calendar Date and used the Dax formula (Calendar function) described below to extract the date (date and time) from the Order date column:

![image](https://user-images.githubusercontent.com/119289961/224690911-387b5947-62b7-476d-9d22-30e6be15d439.png)  
Calendar initiation 

![image](https://user-images.githubusercontent.com/119289961/224691189-1dd91a4c-b0f1-406d-92a4-4cbfe8ef78fc.png)  
Year extraction

• Using the code above, I created a new column and extracted the year from the calendar date;

![image](https://user-images.githubusercontent.com/119289961/224691752-a860b580-32a6-4c3f-b10b-82d8742a5634.png)  
Month extraction

• A new month column was made and also taken from the calendar date column.

![image](https://user-images.githubusercontent.com/119289961/224692228-9eecab6d-3167-4d19-ab34-2123fef576e2.png)  
Yearly difference

Sales totals brake down by continent: 

Europe seems to have the largest sales. Three of the five countries represented in the data were in Europe.

![image](https://user-images.githubusercontent.com/119289961/224692845-ea40099a-ce82-4cd1-8692-b321478f7e84.png)  
Continnet break down

Profits by country

France, Germany, Mexico, the United States, and Canada are the five countries included in the dataset.

![image](https://user-images.githubusercontent.com/119289961/224693231-cff44b19-9255-4e97-a636-5bff700af93d.png)  
Country profit breakdown

Germany and France both have close profit rates; the difference in profits is $100,000. Both are European nations.

Profit by Month

October is the month with the highest sales.

![image](https://user-images.githubusercontent.com/119289961/224694191-481d483e-5014-4f5a-81ea-70ee571713a9.png)  
Monthly Profit

While the month of March has the lowest profit of 0.7 million. This indicates that more sales were made in October, resulting in more profit.

Sum of unit sold per month

The month of October had the highest number of units sold, with 201.01k products sold.

![image](https://user-images.githubusercontent.com/119289961/224694781-e6cbdca1-5a96-48b1-bcb8-8d562a7fcd46.png)  
Unit sold per month

While May has the fewest units sold with 51.42k.

Total sales by category:

The category column categorizes the items into household, cosmetic, and general. General is the company with the most sales.

![image](https://user-images.githubusercontent.com/119289961/224695212-d674eb77-6de6-4147-b92d-709bec3f4835.png)  
Catergory sales

It has over $50 million in sales. This means that the majority of general was purchased.

Total number of units sold by Product

Paseo, a product in the general category, was the most popular. This tells why general is the highest category with sales.

![image](https://user-images.githubusercontent.com/119289961/224695971-469ed225-5a41-452f-97c2-2dd201b56acb.png)  
Unitsold per product

Paseo has sold over 0.3 million units, while Veko and Amarila, Montana and Carretera have sold 0.16 million and 0.15 million units, respectively.

REPORT SUMMARY

The report is three pages long:

 1.The home page 
2.A sales report by location 
 3.A sales report by product
 
 ![image](https://user-images.githubusercontent.com/119289961/224696821-7abf02e5-0510-43e9-aed2-bf1d023b5992.png)  
 Home page
 
![image](https://user-images.githubusercontent.com/119289961/224697117-67e93ee2-dfb9-401c-8a63-4c9d36c543f7.png)  
 location page
 
 ![image](https://user-images.githubusercontent.com/119289961/224697045-07078f9c-30a1-4404-ac00-d01cab6a35ab.png)  
 Product page
 
 RECOMMENDATION

1. The primary goal of a business is typically to maximize profits. More research can be done on products that are losing money to improve them better with lower costs while maintaining their selling price.

2.A marketing campaign can be implemented to attract more potential customers and give existing ones more reasons to purchase a specific product.



