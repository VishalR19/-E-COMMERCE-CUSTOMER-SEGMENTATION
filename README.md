# -E-COMMERCE-CUSTOMER-SEGMENTATION
E-COMMERCE CUSTOMER SEGMENTATION THIS IS THE PROJECT WHERE WE USE THE E-COMMERECE DATA,WE USE THE KMEANS CLUSTERING MACHINE LEARNING ALOGRITHM TO CLUSTER THE CUSTOMER BASED ON THEiR SPENDING
The dataset required for the tasks can be found here:
http://busibud.com/ml_tasks.zip


For this task, we would prefer if you worked on a notebook format for all of the tasks you need to undertake, including data cleaning, transformation, numerical simulation, statistical modeling, data visualization, machine learning, etc. Please make sure it is as expressive as possible.


Task 
Here you would need to create a model which assigns a customer to a certain customer category based on the total value of orders they’ve placed. This would let us target the most valuable customers with certain offers which promote a higher spend. 
The dataset is a CSV, where each row represents an sku which is a part of an order. The different columns are described below. Every conversation included has at least one request from a consumer and at least one response from a company. Which user IDs are company user IDs can be calculated using the inbound field.
Content
InvoiceNo
A single invoice number represents one order that was placed. There might be multiple rows for the same invoice number, representing the different SKUs that were ordered.

StockCode
This represents the sku for the particular item that was ordered.

Description
This describes the exact item that was ordered in words.

Quantity
The quantity of the specific sku that was ordered.

InvoiceDate
This is the date the order was placed.

UnitPrice
This is the price of the particular sku that was ordered.

CustomerID
An anonymized ID of the customer who placed the order.

