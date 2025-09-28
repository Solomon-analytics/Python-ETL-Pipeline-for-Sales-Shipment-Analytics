**Sales Orders & Shipment - Data Pipeline (Python)**
---
This project demonstrates how to build an **end-to-end data pipeline using Python** to process **sales orders and shipment data**, following **Medallion Architecture best practices**.

The pipeline ingests raw data from multiple systems, applies transformations across structured layers (Bronze → Silver → Gold), and delivers **business-ready datasets** for **analysis and reporting**.

* **Bronze Layer**: Ingests raw data (csv files) from multiple source systems (ERP & POS) and stores it in its original format.
* **Silver Layer**: Cleans, standardizes, and consolidates the data while applying validation and enrichment rules.
* **Gold Layer**: Applies business logic and creates fact/dimension-style datasets that are ready for analysis and reporting.

---

## Data Sources
Data is simulated and generated mainly for learning purposes.
* **ERP (Enterprise Resource Planning)** → sales orders, products, store data, shipments.
* **POS (Point of Sales)** → sales transactions, product details, customer information, shipments.

---

## 🛠️ Project Components

### **1. Data Pipeline Architecture**

* Designed an **ETL pipeline** using the **Medallion Architecture** best practices.
* Structured data flow into **Bronze, Silver, and Gold layers** for better governance, scalability, and clarity.

### **2. ETL Process (Python)**

* **Extraction**: Loaded raw CSV data from ERP and POS sources.
* **Transformation**: Applied cleaning (handling duplicates, missing values, inconsistent formats), standardization (currency, dates), and enrichment (derived attributes, validation flags).
* **Loading**: Persisted data at each stage into **Parquet files**, ensuring efficiency and reusability.

### **3. Data Modeling**

* Designed **dimension and fact-style tables** in the Gold layer (customers, products, stores, sales orders, shipments).
* Created business keys and validation flags to support **reliable analytics and reporting**.

### **4. Reporting & Analytics**

* Performed **exploratory data analysis (EDA)** using Pandas, NumPy, Matplotlib, and Seaborn.
* Generated insights into:

  * Customer purchasing behavior
  * Product performance
  * Sales order trends
  * Shipment efficiency & bottlenecks
* Built **Power BI dashboards** to enable stakeholders to monitor KPIs in real-time.

---

## 🎯 Project Objectives

* Build a **Python-based ETL pipeline** that consolidates ERP and POS data.
* Ensure **data quality** through validation, standardization, and cleaning.
* Deliver **business-ready datasets** for analysis and visualization.
* Provide insights that empower stakeholders to make **data-driven decisions**.

---

## 🚀 Outcomes

* Automated recurring ETL workflows, reducing manual reporting time.
* Created **trusted, analysis-ready datasets** in the Gold layer.
* Delivered **interactive Power BI dashboards** that reveal sales trends, customer behavior, and shipment performance.
* Enabled business users to **identify bottlenecks** and optimize supply chain efficiency.
---

Below is the Medallion Architecture (Bronze → Silver → Gold) used in this project:

![]py_erd_diagram.drawio)


