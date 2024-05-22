# Sales & Customer Dashboard
## Introduction
This project contains a Tableau Dashboard to analyze and visualize sales trends and customer behaviour. The dashboard is divided into two main sections:
### Sales Dashboard
This section includes visualizations that track sales performance over time, highlighting key metrics such as total sales, Total Profit, Total Quantity sales by region, Sales by Category and weekly trends.
### Customer Dashboard
This section focuses on customer behaviour, showcasing insights such as Total Customers, Total Orders, Total Sales per Customer, Customer distribution by Number of Orders, top customers and customer order rates.
## Datasets
Below are the details of the Datasets used for the Dashboard:
### Ordes Dataset : 
Key Columns are :
- Row ID: A unique identifier for each row in the table.
- Order ID: Unique identifier for each order.
- Order Date: The date when the order was placed.
- Ship Date: The date when the order was shipped.
- Ship Mode: The shipping mode chosen for the order (e.g., Second Class, Standard Class).
- Customer ID: Unique identifier for each customer.
- Segment: The market segment to which the customer belongs (e.g., Consumer, Corporate).
- Postal Code: Postal code of the customer's location.
- Product ID: Unique identifier for each product.
- Sales: The total sales amount for the order.
- Quantity: The quantity of products ordered.
- Discount: The discount applied to the order.
- Profit: The profit generated from the order.
### Customers Dataset :
Key Columns are :
- Customer ID: Unique identifier for each customer.
- Customer Name: The customer's name associated with the customer ID.
### Location Dataset :
Key Columns are :
- Postal Code: The postal code or ZIP code of the location.
- City: The name of the city corresponding to the postal code.
- State: The state in which the city is located.
- Region: The region or area within the state (if applicable).
- Country/Region: The country or region to which the location belongs.
### Products Dataset :
Key Columns are :
- Product ID: Unique identifier for each product.
- Category: The broad category to which the product belongs (e.g., Furniture, Office Supplies).
- Sub-Category: A more specific category within the broader category (e.g., Bookcases, Chairs).
- Product Name: The name or description of the product.
## Dataset Relationship
Orders Dataset is the main dataset and also has the relationship with Customers, Location and Products Datasets.
<img width="437" alt="Dataset" src="https://github.com/Naimuddin74667/Customer_Sales_Dashboard/assets/71082094/0bd9a484-eb8e-48b6-9630-df03d9e64510">
## Dashboards
### Sales Dashboard
<img width="610" alt="Sales Dashboard" src="https://github.com/Naimuddin74667/Customer_Sales_Dashboard/assets/71082094/72212ba5-a7d2-40b6-929a-9473bdd80471">

- In this dashboard, we can see the details and trends of sales, profit, and quantity, along with their minimum and maximum values.
- We can also view the sales of products by sub-category, along with the previous year's sales.
- Additionally, we can observe the profit by sub-categories.
- We can view the trends of sales and profit over time weekly.
### Customer Dashboard

<img width="611" alt="Customer Dashboard" src="https://github.com/Naimuddin74667/Customer_Sales_Dashboard/assets/71082094/e4a6ccc2-6285-49a9-ba2c-b0743ffe476b">

- In this dashboard, we can observe the details and trends of customers, sales per customer, and orders, including their minimum and maximum values.
- We can also examine the customer distribution by the number of orders.
- Additionally, we can view the top 10 customers with the highest sales and profits, along with their last order date and the number of orders placed.

### Switching between Dashboards
<img align="right" width="608" alt="Switch to Customer Dashboard" src="https://github.com/Naimuddin74667/Customer_Sales_Dashboard/assets/71082094/5540f3c0-2ce8-4565-a41c-6af26ad60970">

- To switch from the **Sales Dashboard to the Customer Dashboard**, simply click on either the Customer or Dashboard icon.

<img align="right" width="608" alt="Switch to Sales Dashboard" src="https://github.com/Naimuddin74667/Customer_Sales_Dashboard/assets/71082094/f910ea44-e699-4d68-a0da-2c4338a96ce0">

- To switch from the **Customer Dashboard to the Sales Dashboard**, simply click on either the Dashboard or Customer icon.

### Apply Filters on Dashboards

<img align="right" width="230" alt="Filter closed" src="https://github.com/Naimuddin74667/Customer_Sales_Dashboard/assets/71082094/12b49889-d55c-441e-8b6c-760a16053c91">
<img align="right" width="242" alt="Filter open" src="https://github.com/Naimuddin74667/Customer_Sales_Dashboard/assets/71082094/00643449-83b2-4e8c-926b-01c306d9762c">

To apply filters, click on the filter icon to open the sidebar filter. After applying the filters, click on the cross icon to close the sidebar.

In the filter, you will find options to select:
- Year
- Category
- Sub-category
- Region
- State
- City
