# Store_Datawarehouse

The **Store_Datawarehouse** project aims to design and implement a modern data warehouse that consolidates sales data from two distinct source systems: **ERP** and **CRM**. The goal is to enable detailed reporting and analytics that provide actionable insights into various business aspects, such as customer behavior, product performance, and sales trends. The project empowers data-driven decision-making through comprehensive **SQL-based reporting**.

## 🛠️ Project Procedures

The project follows a structured approach, encompassing several key phases:

1. **Data Acquisition**: 
   - Raw data is ingested from the two source systems (ERP and CRM) in CSV file format.

2. **Data Quality & Transformation**: 
   - The data is cleaned, transformed, and standardized to ensure consistency and address any data quality issues.

3. **Data Warehouse Architecture**: 
   - The data is organized into a modern data warehouse using the **Medallion Architecture**, divided into **Bronze**, **Silver**, and **Gold** layers.

4. **Analytics and Reporting**: 
   - SQL-based reports are created to extract meaningful insights from the data.

5. **Documentation**: 
   - Comprehensive documentation is provided to support business stakeholders and analytics teams, detailing the data model and transformation logic.

![Procedures of the Project](https://github.com/user-attachments/assets/9cb42eeb-c40f-468a-b0b3-94b03917ca96)

## 🔗 Data Integration

Data integration ensures that disparate data sources are harmonized and accessible for business intelligence and analytics.

![Data Integration](https://github.com/user-attachments/assets/693ebf55-b401-4d69-aae1-9d56c385ae10)

## 🧑‍💻 Data Modeling

Data modeling is a crucial component of this project, optimizing the structure for query performance and analytics. The following steps are involved in the data modeling process:

- **Creating Fact Tables**: Fact tables are designed to store transactional data, such as sales, customer interactions, and product performance.
  
- **Designing Dimension Tables**: Dimension tables store descriptive information related to the facts, such as customer details, product attributes, and time periods.
  
- **Star Schema**: The data model is designed using a **Star Schema**, which is widely used for analytical queries. This schema provides a clear and efficient structure for querying large datasets.

By carefully structuring the data, this phase ensures that the data warehouse is optimized for reporting and analytical queries.
![Data Modelling](https://github.com/user-attachments/assets/c8293c0e-0f49-413b-9c2c-e2f951808403)


## 🏆 Analytics and Reporting

The analytics and reporting phase involves creating SQL-based reports and dashboards to derive insights from the data. Key areas of focus for analysis include:

- **Customer Behavior**: Understanding how customers interact with products and services.
- **Product Performance**: Analyzing sales trends and performance metrics for each product.
- **Sales Trends**: Identifying patterns in sales over time, such as seasonality or geographic variations.

These reports help stakeholders make data-driven decisions, providing insights that are crucial for strategic business planning.
