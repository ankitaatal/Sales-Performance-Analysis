# Superstore Data Insights

About Project
---
This project analyzes sales performance, customer behavior, product trends, and operational logistics using SQL. The dataset contains sales transactions from a fictional retail superstore, allowing us to extract valuable insights into revenue, customer segmentation, product demand, and shipping efficiency.

About Data
---
The dataset consists of 9,999 rows and 21 columns, representing transactional data from a superstore. It has been cleaned and structured into four relational tables:
- customers: Customer information (ID, name, region)
- orders: Order details (date, shipping info)
- products: Product catalog (category, price)
- sales: Sales transactions (quantity, revenue, profit)

Entity Relationship Diagram (ERD)
---
An ERD (Entity Relationship Diagram) is included to visualize relationships between tables.

### 📌 Entity Relationship Diagram (ERD)
An **ERD (Entity Relationship Diagram)** is included to visualize relationships between tables.

📂 Location: [`queries/ERD.mwb`](queries/ERD.mwb)  

![Entity Relationship Diagram](data_cleaning/erd_diagram.png)



 Key Data Insights
---
1. Sales Performance & Revenue Analysis: Understanding revenue trends, profitability, and discount impacts.
2. Customer Behavior & Segmentation: Analyzing customer spending patterns and retention.
3. Product Performance & Market Insights: Evaluating top products, pricing strategies, and market trends.
4. Operational & Logistics Analysis: Improving shipping efficiency and cost-effectiveness.

📂 Project Structure
---
```
📦 Superstore-Analytics
│── 📁 data/               # Contains dataset files
│    ├── README.md         # Detailed dataset description
│    ├── Superstore.csv    # Raw dataset
│
│── 📁 data_cleaning/          
│    ├── data_cleaning.ipynb   # Jupyter notebooks for data cleaning
│    ├── erd_diagram.png       # ERD diagram
│
│── 📁 queries/              # SQL scripts for analysis
│    ├── superstore_db.sql    # Creates database & tables
│    ├── analysis.sql      # SQL queries for business insights
│
│── README.md              # Project documentation (this file)
```











