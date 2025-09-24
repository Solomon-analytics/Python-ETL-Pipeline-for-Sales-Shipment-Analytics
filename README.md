**Sales Orders & Shipment Data Pipeline (Python)**
---
This project showcase how to build an end-to-end data warehouse and reporting solution for sales orders and shipment data using medallion architecture best practices which extract data from ultiple sources and stored in its raw form in a bronze layer, then goes through different layers of transformation with the outcome stored in a silver layer, the final layer is where the business rules are applied and outcome is stored in the gold layer, which indicates the data in this layer is ready for analysis and reporting purposes.

---
The raw data came is sourced from two different systems:
Please note that, all data used in this project is simulated and generated for learning purposes.
- ERP (Enterprise Resource Planning): contains sales orders, product information, store data, and shipment details.
- POS (Point of sales): contains sales transactions, product and store details, customer information, and shipment data.

---

**Project Overview**
---
This project covers the full data lifecycle:
- Data Architecture: Designing a modern Data pipeline using the Medallion Architecture Bronze, Silver, and Gold layers
- ETL Pipelines: Extracting, transforming, and loading data from POS and ERP source systems into the warehouse
- Data Modelling: Designed a star schema for orders, shipments, customers, and products, supporting scalable analytics.
- Analytical & Reporting creating SQL-based reports using Views and dashboards to deliver actionable insights for stakeholders.

---

**Project Requirements**
---
**Building the sales orders and shipment data warehouse (Python)**

**Objective:**
Develop a modern data warehouse using Python to consolidate data from POS and ERP sources for each of the data fr sales, shipment, stores, store products, products, sales person, making it ready for analysis and reporting.

**Key Features**:
- **Data Extraction & ETL**: Used Python (Pandas) to extract raw sales, customer, and shipment data from multiple CSV/SQL sources.
- **Data Quality**: Cleaned and transformed datasets (handling duplicates, missing values, and inconsistent formats).
- **Data Integration**: Consolidate data from ERP and POS into a single, user-friendly data model designed for analytical queries and reporting.
- **Automation**: Built Python scripts to automate ETL workflows, reducing manual processing.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics team.

---

## Data Analysis (Business intelligence & Reporting)

**Objective**:
Develop a list of analytics reporting using Pandas, Numpy, Matplotlib, Seaborn to uncovers insights into:
- Customer Purchasing Behaviour
- Product Performance
- Sales Orders Trends
- Shipment Efficiency
  These insights empowers stakeholders within the business identofy/track key business metrics, enabling informed decision-making

  ---

**Outcomes**:

- Automated recurring analysis of orders and shipments, reducing reporting time.
- Aim to deliver inteactive Power BI dashboards that provide actionable insights into sales trends, shipment delays, and customer behaviour.
- Aim to enable business users to identify bottlenecks and optimise supply chain efficiency.


