
# Project Background

Universal Export is a B2B garment manufacturing company based in Southampton, United Kingdom, supplying plain, unlabeled and unmarked garments for consumers like retailers and wholesalers. 

This report presents an overview of the company’s business operations for 2023. It is designed to help shareholders gain insights into their investments and for managers to make data-driven decisions by visualizing overall sales, product-level distribution and regional performance. 

It aims to:
- Provide a detailed understanding of the company’s sales and profits for 2023.
- Offer Insights into the types of products in various categories that are sold and identify the best products. 
- Compare sales performance across various regions.
- Provide an overview of the logistics used.

The data cleaning steps and DAX formula used to transform the data for this analysis can be found here https://github.com/Lakshya-attavar/PowerBI-SalesReport/blob/main/Sales_Report_DAX.pdf.

An interactive PowerBI report used to report and explore sales trends can be downloaded from here 
https://github.com/Lakshya-attavar/PowerBI-SalesReport/blob/main/SalesReport-Manufacturing.pbix.

## Data Structure & Initial Checks

The company’s main database structure as seen below consists of four tables: Products, Transactions, Customers and Logistics. A description of each table is as follows:
* Products: The products table contains information on the ID, name, category, colour, price per unit and cost of the products sold by Universal Export.
* Transactions: The Transactions table consists of 11 columns with details about the orders including their ID, date, total price, customer ID, logistic ID, shipment city, shipment country, products ordered, quantity, price and cost info
* Customers: The customer’s table has 8 columns with details of customers’ ID, name, address, year of the first order, business category, salesperson ID, email and if they are new customers.
* Logistics: The logistics file(txt) includes details of logistic ID, name, type, office location, email and contact number separated by semicolon delimiter. 
<img width="708" alt="Pasted Graphic 20" src="https://github.com/user-attachments/assets/7ccc91c2-f96a-42e0-9d0b-79fc8ad840a8">
## Executive Summary

### Overview of Findings
The company’s revenue increased starting at the beginning of the year, with Qtr 3 bringing in the highest. The revenue saw a slight drop following Qtr3 for the rest of the year. Profits followed a comparable trend to revenue, with a total profit of 467M for the year.  The United Kingdom was the largest customer in terms of both sales and Revenue. The following sections will explore the overall operational status for 2023 in detail.

## Insights Deep Dive

### Sales and Profitability Overview:

* The company has made a total revenue of 1040 M and a profit of 467.1  M in 2023.
* The company’s revenue and profits increased since the beginning of the year, with Quarter 3 making the highest profits.  New customers constituted 12M of the 15M increase between Qtr2 and Qtr3. 
* The month of August has seen the highest revenue of 93M and thereby profit of 42M. The second half of the year has seen higher sales and profits, showing better performance. Universal Export offers a wide variety of t-shirts and hoodies which are summer and autumn-appropriate clothing, and hence demand for t-shirts and hoodies slightly rose in the second half. Also, most of the orders from new customers have been made in the second half of the year accounting for the increased revenue during that time.
<img width="1001" alt="Sales and Profitability Overview for 2023" src="https://github.com/user-attachments/assets/8ddd893b-d26a-403e-bf06-1c8b2a3380d0">


### Product Portfolio:

* Universal Export’s product catalogue includes a wide range of plain garments categorised into 6 categories, T-shirts, Hoodies, Sweatshirts, Polo Shirts, Cardigans and Jackets respectively, offering a range of styles and colour options. 
* T-shirts and Hoodies are the best-selling categories, together contributing to approximately 51.3% (32M) of quantities sold overall. This is owed to the wide variety of products in various colours available in these categories. The T-shirts and Hoodie categories have the largest range of products with 28 products each.
* In terms of revenue, Hoodies, one of the best-selling categories took first place generating 271 M, contributing to 26.09 % of the total revenue and 32.5% (152M) of the total profits. The most popular products in this category i.e., Xtra sport hoodie for Athletes is also the most profitable. While T-shirts are best-sellers, their contribution to revenue and thereby profits remains low since they have a lower selling price.
* In terms of profitability, The Xtra Sport for Athlete line in Hoodie has the highest profit margin of 68.75%, contributing to 18.85% of the total profits. This line of products is the strongest product for the company, and Alpha V2 polo shirts with the lowest profit margin and lower profits are the weakest products.
<img width="836" alt="Product Portfolio" src="https://github.com/user-attachments/assets/e93681ae-42d8-4e5d-8ea9-85ea9a7e8f28">

### Regional Distribution:

* Universal Export has a large customer base with 48 customers from 22 countries. The company received orders from across the UK and Europe with the United Kingdom being its largest customer in terms of sales. In 2023, a total of 35K orders were shipped out, 8.5K of which were from the UK and the rest from across multiple markets in Europe.
* With the UK being the largest contributor of revenue at 249M, the countries of Spain, France and Germany are among the top revenue-generating countries in Europe. These four countries contribute to almost 50% of the total revenue and profits, playing a significant role in the company’s financial performance. Universal Export’s partnerships with international retailers, wholesalers and reliable logistics partners played a pivotal role in expanding sales across various markets in Europe.
<img width="1001" alt="Regional Distribution" src="https://github.com/user-attachments/assets/057e76bc-e2ce-4c69-9848-6827abee4ff0">

### Logistics Review:

* All orders are shipped through three primary modes of shipment including Air, Land, Sea and a fourth mixed mode combining all three. Air shipment and the mixed mode are the most used shipment modes as observed below.
* The no. of Air Shipments has increased post-July. This year Universal Export has also taken up a sustainability commitment with an aim to reduce carbon emissions produced by its supply chain and Logistics operations. As a part of the sustainability initiative, the company committed to reducing shipments exclusively through Air from the 1st of July 2023 to the end of the year. However, a notable increase in the number of air shipments was observed through the months in the second half of the year due to several challenges. The number of international orders slightly rose in the second half of the year, and air transport became the most preferred mode of international shipments. An increase of 500 shipments by air occurred post-July compared to the first half of the year as observed below. While this was disappointing, the slight increase in air transport was a well-thought-out decision that Universal Export needed to make to maintain its position in the market as well as cater to the clients.
<img width="1001" alt="Logistics Review - Sustainability Commitment" src="https://github.com/user-attachments/assets/ee1cd63d-43d6-41e9-bdaa-1ad1e193b0a5">

## Recommendations:
Based on the insights and findings above, we would recommend the managers to consider the following:
* Hoodies and T-shirts are the best-selling products. The Xtra Sport Hoodie for Athletes series of hoodies are the most popular products in terms of sales and have a high profit margin making them strong products for the company. Widening the colour options for the Xtra Sport Hoodie for Athlete product range and also focusing on improving other hoodies and T-shirts would lead to increased profits.
* The Alpha V2 polo shirts for Special Comfort have lower profit margins and lower sales volume making them a weaker product. Improvements to this product or its continuity for the next year should be considered.
* The countries UK, Spain, France and Germany constitute about 50% of the profits. Focusing on these key markets can be beneficial for the long-term financial growth of the company.
* Despite the efforts to reduce Air shipment in the second half of the year, a notable increase is observed due to the increased number of international orders. Since a boost in international orders means better financial performance, other modes of shipment to cater to European clients must be sought to keep up with the company’s sustainability commitment.


