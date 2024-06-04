# Coffee-Sales-Analysis
## Table of Contents
- [Glossary](#glossary)
- [Project Overview](#project-overview)
- [Data sources used](#data-sources-used)
- [Dataset Columns](#dataset-columns)
- [Data Cleaning and Preparation Processes](#data-cleaning-and-preparation-processes)
- [Stakeholder questions](#stakeholder-questions)
- [Insights gotten from the analysis](#insights-gotten-from-the-analysis)

## Glossary
- Sales: This refers to any transactions where money or value is exchanged for the ownership of a good or service.
- Footfall: These are the number of people entering a shop in a given time.
## Project Overview
The objective of the project is to answer stakeholder questions from a "coffee shop sales" CSV file containing different products which allows the business to assess how well it is doing and what recommendations can be given based on the insights from the analysis.
## Dashboard
![Coffee Shop Sales](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/f349faf4-93a6-48dd-920e-513f40fae9a7)



## Data sources used
The data set used was the coffee shop sales.csv file with the finished product saved as a workbook.
The original file is stored in the zip.
## Dataset Columns
- Transaction_id: the unique identifier of purchase made.
- Transaction_date: the date of the purchase.
- Transaction_time: the time the product was bought.
- Transaction_qty: number of items bought.
- Store_id: The distinct code of each store.
- Store_location: the location store of where the transaction was made.
- Product_id: the unique code for identifying each product.
- Unit_price: the price of one item.
- Product_category: the category of the product.
- Product_type: the type of product.
- Product_detail: the name of the product.
- Day: the day of the week the item was bought.
- Month: the month of the year the item was bought.
- Hour: the hour of the day the item was bought.
- Total_bill(revenue): the total bill for each transaction which serves as our revenue.
## Tools used
- Excel: A spreadsheet software.
## Data Cleaning and Preparation Processes
- Checked for null values
- Feature engineering  functions include:
- - TEXT: Used to extract day and month from the transaction date column
  - HOUR: To get the hour from the transaction time column
  - Formula for revenue = transaction_qty * Unit_price

## Stakeholder questions
All these questions can be found in the PDF file
1. How do sales vary by day of the
week and hour of the day?
2. Are there any peak times for sales
activity?
3. What is the total sales revenue for
each month?
4. How do sales vary across different
store locations?
5. what is the average price/order
per person
6. Which products are the bestselling in terms of quantity and
revenue?
7. How do sales vary by product
category and type?

## Insights gotten from the analysis
1. From the analysis one understands that the  most profitable day is on Monday(typically because that is the start of the week) and Saturday bringing in the least sales and footfall numbers(i.e. customers).<br /><br />![total sales and footfall by day of the week](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/069cea9f-38a7-49ad-8e7b-241780b529ec)

2. The data shows us that across all stores businesses start getting busy at 8:00 am and get the busiest by 10:00 am. So to get more sales the coffee shop can advertise the "Barista Espresso" (the most purchased product) primarily sold from 8 am to 10 am to encourage customers to  come back during the stated time consistently with also the staff having the beverage produced at excess.<br /><br />![hourly trend of orders placed by customers](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/eb861faa-c015-4e9b-829c-3325c15cc229)

3. The monthly revenue visualisation explains to stakeholders that most revenue is gotten in June and least in February with a possible steady increase after June throughout the year.<br /><br />![total revenue for each month](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/b2ec4b9e-2c6c-4e45-925c-6f7966e35929)

4. The dashboard explains to us that Hell's Kitchen brings in the most revenue and customers.<br /><br /> ![total revenue and footfall by store location](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/c8f432a9-a95b-444d-a4fd-0ba998819089)


5. The average bill of a customer is £4.69. Furthermore, the information also displays the total sales, total footfall, average bill/person & average order/person <br /><br /> ![total sales, average](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/605ae5dc-8a2d-4506-ad65-1b12603071c5)

6. The top-selling products ( in ranked order) across all stores include:
   - Barista Espresso(£91,406.20)
   - Brewed Chai Tea(£77,081.95)
   - Hot Chocolate(£72,416.00)
   - Gourment Brewed coffee(£70,034.60)
   - Brewed Black Tea(£47,932.00)
   <br /><br /> ![top selling products](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/e12a56fc-bc53-46d9-ac95-3057ef938d65)
8. The pie chart shows the most sold categories are Coffee and Tea. Likewise, this relates to the previous question with expresso and chai tea being the first and second most sold products respectively.<br /><br />![Categories % distribution based on sales](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/9a5a28cf-d426-4254-b002-01eeabfa977d)


  







