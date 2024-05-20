# Coffee-Shop-Sales-Analysis
Coffee Shop Sales Data Dictionary
transaction_id: Unique sequential ID representing an individual transaction

transaction_date: Date of the transaction (MM/DD/YY)

transaction_time: Timestamp of the transaction (HH:MM:SS)

transaction_qty: Quantity of items sold

store_id: Unique ID of the coffee shop where the transaction took place

store_location: Location of the coffee shop where the transaction took place

product_id: Unique ID of the product sold

unit_price: The retail price of the product sold

product_category: Description of the product category

product_type: Description of the product type

Using Power Query, I cleaned the dataset and added new columns such as day name, month name, hour, and a custom column for the total bill (calculated as unit price * quantity). I also extracted data from one column to create a new column, size, derived from the product detail column.

With this refined dataset, I used pivot tables to address the following questions:

How do sales vary by day of the week and hour of the day?

Are there any peak times for sales activity?

What is the total sales revenue for each month?

How do sales vary across different store locations?

What is the average price per order per person?

Which products are the best-selling in terms of quantity and revenue?

How do sales vary by product category and type?

Finally, I created an interactive dashboard to present these insights visually.

The fundamental aim of this initiative is to meticulously scrutinize retail sales data to derive actionable insights, thereby fostering improvements in the operational efficacy of the Coffee Shop.
