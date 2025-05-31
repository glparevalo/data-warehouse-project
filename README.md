# 📦 Data Warehouse Project

> A robust SQL Server-based Data Warehouse solution designed for efficient ETL, modern data modeling, and data analysis. 

---

## 🔍 Project Overview

This project demonstrates how to build a scalable and optimized **Data Warehouse using SQL Server**. It integrates data from multiple sources, applies transformations, and supports advanced analytical queries for reporting. This is a guided project with the help of Baraa Balzini.


## 📚 Table of Contents

- [🔍 Project Overview](#-project-overview)
- [🏗️ Architecture](#️-architecture)
- [🧱 Schema Design](#-schema-design)
- [📄 License](#-license)

---

## 🏗️ Architecture

[Data Sources] --> [Bronze Layer] --> [Silver Layer] --> [Gold Layer]

- **Data Sources:** CRM and ERP data sources in csv format.
- **Medallion Architecture:** Having Bronze, Silver, and Gold Layer.

---

## 🧱 Schema Design

### Star Schema

[dim_customers] ---- [fact_sales] ---- [dim_products]

- **Fact Table:** `fact_sales`
- **Dimensions:** `dim_customer`, `dim_products`

## 📄 License
This project is licensed under the MIT License.
