# Retail-Store-Sales-ML-Project

This project focuses on cleaning, preprocessing, and modeling a real-world retail dataset containing 12,575 transactions. A significant portion of the data (~4,000 rows) had missing values in the Discount Applied column.
<br>
<br>
Rather than filling missing values using simple methods like mean/median/mode, this project uses machine learning to predict missing discounts based on item categories, prices, quantities, and more.
<br>
<br>
<H1> Attribute Information </H1>
<br>
| Column Name          | Non-Null Count | Type   | Description                                            |
<br>
<br>
| Transaction ID       | 12,575         | object | Unique ID for each transaction                         |
<br>
<br>
| Customer ID          | 12,575         | object | ID of the customer                                     |
<br>
<br>
| Category             | 12,575         | object | Product category                                       |
<br>
<br>
| Item                 | 11,362         | object | Item purchased (contains missing values)               |
<br>
<br>
| Price Per Unit       | 11,966         | float  | Price per product                                      |
<br>
<br>
| Quantity             | 11,971         | float  | Number of units purchased                              |
<br>
<br>
| Total Spent          | 11,971         | float  | Total transaction amount                               |
<br>
<br>
| Payment Method       | 12,575         | object | Payment method used                                    |
<br>
<br>
| Location             | 12,575         | object | Store location                                         |
<br>
<br>
| Transaction Date     | 12,575         | object | Date of purchase                                       |
<br>
| **Discount Applied** | **8,376**      | object | Discount category applied (target with missing values) |
<br>
<br>
<H1>Goal</H1>
<br>
Instead of using mean ,median mode or probabilistic imputation i have used multiple ML models and selected the one with the best accuracy 
