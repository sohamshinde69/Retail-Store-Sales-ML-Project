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
| -------------------- | -------------- | ------ | ------------------------------------------------------ |
| Transaction ID       | 12,575         | object | Unique ID for each transaction                         |
| Customer ID          | 12,575         | object | ID of the customer                                     |
| Category             | 12,575         | object | Product category                                       |
| Item                 | 11,362         | object | Item purchased (contains missing values)               |
| Price Per Unit       | 11,966         | float  | Price per product                                      |
| Quantity             | 11,971         | float  | Number of units purchased                              |
| Total Spent          | 11,971         | float  | Total transaction amount                               |
| Payment Method       | 12,575         | object | Payment method used                                    |
| Location             | 12,575         | object | Store location                                         |
| Transaction Date     | 12,575         | object | Date of purchase                                       |
| **Discount Applied** | **8,376**      | object | Discount category applied (target with missing values) |
