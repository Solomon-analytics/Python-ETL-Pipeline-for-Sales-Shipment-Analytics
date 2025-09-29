# Python ETL Pipeline for Sales & Shipment Analytics

This project shows how I built an end-to-end **ETL pipeline in Python** to process and prepare **sales orders and shipment data** for analysis and reporting. The pipeline follows the **Bronze → Silver → Gold layered approach**, which keeps raw data separate from cleaned and business-ready datasets.

---

## Project Workflow

**Bronze Layer**

* Loads raw CSV data from ERP and POS sources.
* Stores the files in their original format without changes.

**Silver Layer**

* Cleans and standardises the data.
* Fixes duplicates, missing values, and inconsistent formats.
* Applies validation and adds derived fields where needed.

**Gold Layer**

* Applies business rules.
* Creates fact and dimension-style tables (customers, products, stores, sales orders, shipments).
* Produces datasets that are ready for analysis and reporting.

---

## Data Sources

* **ERP system**: sales orders, products, store data, shipments
* **POS system**: sales transactions, product details, customer information, shipments
  
 **Note on Data**: This project uses **synthetic data generated for learning purposes**. However, the processes documented in this project demonstrates how the same
  method could be applied to real business data.

---

## Tools and Methods

* **Python (Pandas, NumPy)** for ETL steps.
* **Matplotlib & Seaborn** for exploratory data analysis and visualisations.
* **Parquet** for storing datasets efficiently at each stage.
* **Power BI** for dashboards and reporting.

---

## Analysis & Insights

From the Gold layer datasets, I explored and reported on:

* Customer purchase and revenue analysis
* Product performance across categories
* Sales and revenue analysis
* Order fulfilment efficiency (order creation --> shipment)

Interactive **Power BI dashboards** were built to make these insights accessible to stakeholders.

---

## Outcomes

* Automated the end-to-end ETL process in Python, reducing manual reporting effort.
* Produced clean, reliable datasets that can be reused for different analyses.
* Delivered dashboards that highlight sales trends, customer behaviour, and shipment bottlenecks.
* Helped demonstrate how better data preparation improves decision-making and supply chain visibility.

---

Below is the workflow used in this project:

![](py_erd_diagram-Page.svg)




