# Online-Store-Data-Analysis
This repository contains code and resources for conducting analysis of an online store data. The purpose of this project is to explore, analyse, and derive insights from a dataset related to online store orders. The analysis encompasses various aspects &amp; factors influencing various orders.

## Project Overview

This repository contains code and resources for conducting analysis of an online store data. The purpose of this project is to explore, analyze, and derive insights from a dataset related to online store orders. The analysis encompasses various aspects &amp; factors influencing various orders.

![Dashboard](online_store_report_screenshot.png)

###  Data Sources

Online Store Data: The primary dataset used for this analysis is the "online_store_data_analysis.xlsx" file, containing detailed information about orders.

  - This spreadsheet contains 2 sheets & 6 pivot table sheets:
    - Store Report 2022: main dashboard contains all the reports and charts
    - Data Set: contains the main data on which we performed data cleaning, processing and analysis
    - Sales vs Orders, Men vs Women, Order Status, Order Status, Sales: Top 5 States, Age & Gender, Order Channels: contains pivot charts information

### Tools

- Microsoft Excel: Data cleaning, data processing, data analysis & visualization

## Approach for Data Analysis
1. Ask: ask questions & define problem
2. Prepare: prepare data by collecting & storing information
3. Process: process data by cleaning & checking information
4. Analyse: analyse data to find patterns & trends
5. Share: share data with audience
6. Act: act on data & use analysis results

### ASK
- Compare the sales and orders using single chart
- Which month got the highest sales and orders?
- Who purchased more - men or women in 2022?
- What are different order status in 2022?
- List top 10 states contributing to the sales?
- Relation between age and gender based on number of orders
- Which channel is contributing to maximum sales?
- Highest selling category?

### PREPARE
- We received our dataset from kaggle
- You can search for different datasets in kaggle
- Link: https://www.kaggle.com/

### Data Cleaning/Preparation

- Cleaned the null values from all the columns of the dataset
- Replaced redundant data with uniform data
- 

### Exploratory Data Analysis

EDA involved exploring the hotel booking data to answer key questions, such as:
- What is the overall hotel cancellation trend?
- Which type of group cancelled most of the hotel bookings?
- What are the peak cancellations periods?
- Whether people got the desired room which they opt for or not?

### Data Analysis

Include some interesting code/features worked with

- Checking whether people got the desired room which they opt for or not?:
```
=IF([@[reserved_room_type]]=[@[assigned_room_type]],"desired","undesired")
```

- For finding out type of guest (Couples, Singles or Family):
```
=IF(AND(E2=2,F2=0,G2=0),"Couples",IF(AND(E2 = 1, F2 = 0, G2 = 0),"Single","Family"))
```

### Results/Findings

The analysis results are summarized as follows:
1. Total bookings: 119391, Total cancellations: 44224
2. Overall the month of August witnessed the highest number of bookings
3. City hotel bookings were greater as comparison to resort hotel bookings
4. Couples booked the most hotels so it is obvious cancellations will also be greater
5. Most of the customers received their desired rooms according to the reservations

### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak holiday seasons to maximize revenue
- Focus on promoting your accomodations features such as affordability and accessibility so that we can increase the numbers in category of singles and family members
- Introduce more hotel packages for singles which targets the weekends + fridays or mondays 

### References
- Kaggle: https://www.kaggle.com/datasets/mojtaba142/hotel-booking
