# Retail-Operations-Database-System
**Optimizing Retail Operations: A Comprehensive  Database System for Order Management, Sales  Analytics, and Customer Insights.
**

This project focuses on designing and implementing a relational database system to optimize data management for a global retail operation. By addressing challenges like scalability, data integrity, security, and advanced analytics, the system streamlines operations and enhances decision-making for retail businesses.

Data Source: 
We used the Global Superstore Dataset as our primary data source. Additional unique identifiers were generated using Python’s Faker library to facilitate relational mapping and schema design.  https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset/data

Tables and Schema: 
The database consists of the following key tables:
	1	Orders: Tracks customer orders and priorities.
	2	Order_Details: Links orders to product details.
	3	Products: Contains information about products and their categories.
	4	Customers: Stores customer data, including segments and market associations.
	5	Shipping: Tracks shipping details like cost and mode.
	6	Sales: Stores sales and profit data.
	7	Address: Manages customer and shipment address details.
	8	Market: Contains market region details and status.
	9	Categories: Tracks product categories and subcategories.

Features and Functionalities: 
	•	Data Normalization: All tables adhere to BCNF principles, ensuring consistency and eliminating redundancy.
	•	SQL Queries: Demonstrated complex query executions, including joins, aggregations, and optimizations for advanced analytics.
	•	Indexing: Applied indexing to improve query performance for large datasets.
	•	Streamlit Integration: A user-friendly interface for running dynamic queries and visualizing results.

Database Integration and Loading:
	•	Tables Creation: Designed using create.sql.
	•	The database was created by initially importing the .csv dataset into a mega table to consolidate the data. 
	•	Data Loading: Data was imported into PostgreSQL using load.sql.

Query Demonstrations:
Several queries were executed and optimized to showcase the system's capabilities:
	•	Identifying underperforming markets.
	•	Finding top-performing products.
	•	Analyzing high-cost shipping orders.
	•	Calculating average shipping costs by mode.

Results and Report: 
The analysis, optimizations, and insights derived from the queries are documented in the final report.
Tools and Technologies
	•	Database Management System: PostgreSQL
	•	Programming Language: Python
	•	Libraries: Faker, Pandas, Plotly, Streamlit
	•	ER Diagram Tool: dbdiagram.io

Conclusion: 
This project highlights the importance of a well-designed database system for managing and analyzing large-scale retail operations. By replacing traditional tools like Excel, the system ensures scalability, efficiency, and actionable insights for various stakeholders.
