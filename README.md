# E-commerce Order Status Tracker using Excel and Power BI 

**Project Overview**
This project is designed to streamline workflow tracking across multiple departments (e.g., Evaluation, Inspection, Certification). It centralizes task progress, automates status updates, and enhances inter-departmental coordination. Built using Excel and optionally integrated with Power BI, the system ensures timely project completion with complete visibility across teams.**

**Objectives**

Track the lifecycle of customer orders across multiple departments.
Analyze delays and status breakdowns in the order delivery pipeline.
Improve coordination among Sales, Warehouse, and Logistics teams.
Visualize KPIs like delivery time, late orders, and order statuses.

**Tools & Technologies**

Microsoft Excel (for tracking and processing)
Power BI (for creating interactive visual dashboards)
Formulas Used: IF, VLOOKUP, DATEDIF, COUNTIFS, Conditional Formatting
Dataset Source: Kaggle – E-Commerce Public Dataset

**Key Features**

Order Status Tracker: Visual breakdown of orders by stage (Processing, Shipped, Delivered, Cancelled)
Delivery Time Analysis: Average, minimum, and maximum delivery times by category or region
Departmental Workflow View: Simulates how different teams (Warehouse, Delivery, Returns) interact
Late Order Detection: Flag orders exceeding SLA (Service-Level Agreement) timelines
Interactive Power BI Dashboard: Filters by city, product category, order status, etc.

**Dataset**

Source: Brazilian E-Commerce Public Dataset
Tables Used:
orders.csv
order_items.csv
order_status.csv
products.csv
customers.csv
sellers.csv

**Insights Gained**

Identified regions with the highest delivery delays
Tracked cancellation rates by product category
Improved visibility into warehouse-to-logistics handoffs
Flagged systemic bottlenecks in order processing

**How to Use This Project**

Download the dataset from Kaggle.
Load and clean the data in Excel or Power BI using Power Query.
Apply formulas and create visuals to track key order metrics.
Use slicers in Power BI to explore department-wise workflows and trends.

**Future Enhancements**

Integrate customer satisfaction survey data to correlate with delivery metrics
Build alerts for pending or aging orders
Create a web-based dashboard using Streamlit or Flask (optional)













