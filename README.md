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
This project aimed to get ad-hoc insights from the CSV file which contains all the transactions of different customers of the "Coffee Shop Sales" chain in America. This was done by cleaning and transforming the data via feature engineering using functions and formulas to answer stakeholder questions and improve business performance.
## Dashboard
![Coffee Shop Sales](https://github.com/Tyroneekhator/Coffee-Sales-Analysis/assets/72547969/f349faf4-93a6-48dd-920e-513f40fae9a7)



## Data sources used
The data set used was the coffee shop sales.csv file with the finished product saved as a workbook.
The original file is stored in the zip.
## Dataset Columns
- Transaction_id
- Transaction_date
- Transaction_time
- Transaction_qty
- Store_id
- Store_location
- Product_id
- Unit_price
- Product_category
- Product_type
- Product_detail
- Day
- Month
- Hour
- Total_bill(revenue)
## Tools used
- Excel: A spreadsheet software.
## Data Cleaning and Preparation Processes
- Checked for null values
- Feature engineering  functions include:
- - TEXT: Used to extract day and month from the transaction date column
  - HOUR: To get the hour from the transaction time column
  - Formula for revenue = transaction_qty * Unit_price

## Stakeholder questions
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
1. From the analysis one understands that the  most profitable day is on Monday(typically because that is the start of the week) and Saturday bringing in the least sales and footfall numbers(i.e. customers). 
2. The data shows us that across all stores businesses start getting busy at 8:00 am and get the busiest by 10:00 am. So to get more sales the coffee shop can advertise the "Barista Espresso" (the most purchased product) primarily sold from 8 am to 10 am to encourage customers to  come back during the stated time consistently with also the staff having the beverage produced at excess.
3. The monthly revenue visualisation explains to stakeholders that most revenue is gotten in June and least in February with a possible steady increase after June throughout the year.
4. The dashboard explains to us that Hell's Kitchen brings in the most revenue and customers.
5. The average bill of a customer is £4.69
6. The top-selling products ( in ranked order) across all stores include:
   - Barista Espresso(£91,406.20)
   - Brewed Chai Tea(£77,081.95)
   - Hot Chocolate(£72,416.00)
   - Gourment Brewed coffee(£70,034.60)
   - Brewed Black Tea(£47,932.00)
7. The pie chart shows the most sold categories are Coffee and Tea. Likewise, this relates to the previous question with expresso and chai tea being the first and second most sold products respectively.
   


  







