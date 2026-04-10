# 📊 Data Warehouse & Analytics Project (SQL Server)

Welcome to the **Data Warehouse and Analytics Project** 🚀  
This project demonstrates an end-to-end **data engineering solution**, from raw data ingestion to analytical reporting using a modern data warehouse.

---

## 🎯 Objective
Build a **modern Data Warehouse using SQL Server** to consolidate sales data from multiple sources and enable:
- Analytical reporting  
- Business insights  
- Data-driven decision-making  

---

## 📌 Project Overview
This project covers:

- 🏗️ Data Architecture (Medallion Architecture)
- 🔄 ETL Pipelines (Extract, Transform, Load)
- 🧩 Data Modeling (Fact & Dimension Tables)
- 📊 Analytics & Reporting (SQL-based insights)

---

## 🏗️ Data Architecture

The project follows **Medallion Architecture**:

### 🥉 Bronze Layer (Raw Data)
- Stores raw data from ERP & CRM systems  
- Loaded from CSV files into SQL Server  
- No transformations applied  

### 🥈 Silver Layer (Cleaned Data)
- Data cleansing and preprocessing  
- Standardization and normalization  
- Data enrichment  

### 🥇 Gold Layer (Business Data)
- Business-ready structured data  
- Star schema (Fact & Dimension tables)  
- Optimized for reporting  

---

## 📷 Architecture Diagram

<p align="center">
  <img src="architecture.png" alt="Data Warehouse Architecture" width="800"/>
</p>

---

## 🔄 ETL Pipeline

### 1. Extract
- Sources: ERP & CRM  
- Format: CSV files  
- Batch processing  

### 2. Transform
- Data cleaning (null handling)  
- Standardization & normalization  
- Data integration  

### 3. Load
- Bronze → Silver → Gold  
- Stored as analytical tables  

---

## 📂 Data Sources
- ERP system (CSV files)  
- CRM system (CSV files)  

---

## 🧹 Data Quality Handling
- Removed duplicates  
- Handled missing values  
- Standardized formats  

---

## 🧩 Data Modeling
- Fact Tables: Sales, Transactions  
- Dimension Tables: Customer, Product, Time  

Schema:
- ⭐ Star Schema  
- 📊 Aggregated Tables  

---

## 📊 Analytics & Reporting
- SQL queries for insights  
- Dashboard-ready datasets  
- Ad-hoc analysis  

---

## 🛠️ Tech Stack
- SQL Server  
- SQL  
- CSV / Excel  

---

## 💼 Skills Demonstrated
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- SQL Development  
- Analytics  

---

## 🚀 Use Case
Perfect for:
- Students (Portfolio)  
- Data Analyst / Data Engineer roles  
- Internship applications  
