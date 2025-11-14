# Retail-Store-Sales-ML-Project

This dataset originally contained 12,575 rows, with over 4,000 missing values in the discount_applied column. Instead of using simple statistical imputation methods (mean/median/mode), I applied a probability-based approach using patterns from other relevant features.
<br>
<br>
<h1>Goal</h1>
<br>
 Split the data into two groups:
<br>
 Rows with known "discount_applied" values 
  <br>
Rows with missing values

<br>
Trained and evaluated four different machine learning models on the complete portion of the dataset

Selected the best-performing model and used it to predict the missing discount_applied values
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
