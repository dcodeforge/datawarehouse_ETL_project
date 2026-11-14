# 🏗️ Modern Data Warehouse & ETL Project

A modern data warehouse solution built using **Medallion Architecture**, consisting of three layers: Bronze, Silver, and Gold. This project demonstrates how raw data can be ingested, transformed, cleaned, and organized into structured datasets for analytical and reporting purposes.

---

## 📌 1. Project Components

The project is organized into the following major components:

### 🥉 Bronze Layer – Raw Data
- Stores raw data from source systems.
- Maintains the original structure of incoming data.
- Supports initial data ingestion and loading.
- Preserves source data for further processing.

### 🥈 Silver Layer – Cleaned Data
- Performs data cleansing and transformation.
- Handles missing values and duplicate records.
- Standardizes data formats and structures.
- Improves data consistency and quality.

### 🥇 Gold Layer – Business-Ready Data
- Stores refined and business-ready datasets.
- Organizes data for analytical requirements.
- Supports reporting and business intelligence.
- Provides a reliable foundation for decision-making.

---

## 🎯 2. Problem Statement

Organizations often collect data from multiple sources in different formats and structures. Raw data may contain inconsistencies, duplicate records, missing values, and quality issues.

Without a structured data management process, it becomes difficult to maintain data quality, perform efficient analysis, and generate meaningful business insights.

**The objective of this project** is to develop a modern data warehouse using a structured ETL process that transforms raw data into clean, consistent, and analytics-ready information.

---

## 💡 3. Solution

This project implements a **Medallion Architecture** with three processing layers to organize and manage the data efficiently.

The ETL workflow follows these steps:

1. **Extract:** Collect raw data from the available source datasets.
2. **Load:** Ingest the raw data into the Bronze Layer.
3. **Transform:** Clean, standardize, and validate data in the Silver Layer.
4. **Refine:** Prepare structured, business-ready datasets in the Gold Layer.
5. **Analyze:** Make processed data available for reporting and analytical purposes.

### 🔄 Data Architecture

```text
       📂 Source Data
             |
             ▼
     🥉 Bronze Layer
       Raw Data
             |
             ▼
     🥈 Silver Layer
   Cleaned & Transformed
             |
             ▼
      🥇 Gold Layer
   Business-Ready Data
             |
             ▼
     📊 Analytics & BI
```

---

## 📁 4. Folder Structure

The repository is organized into datasets, documentation, and scripts.

```text
datawarehouse_ETL_project/
│
├── 📂 datasets/
│   └── Source datasets
│
├── 📂 docs/
│   └── Project documentation
│
├── 📂 scripts/
│   ├── 📂 bronze/
│   │   └── Bronze layer ETL scripts
│   │
│   ├── 📂 silver/
│   │   └── Silver layer ETL scripts
│   │
│   └── 📂 gold/
│       └── Gold layer ETL scripts
│
├── 📄 README.md
│
└── 📄 LICENSE
```

*Note: The repository currently contains the `datasets`, `docs`, and `scripts` top-level folders. The layer-specific folders above illustrate the intended organization; adjust them to match your actual script directories.*

---

## 📈 5. Project Outcomes

Through this project, the following outcomes are targeted:

- ✅ Implementation of a structured Medallion Architecture.
- ✅ Organized raw, cleaned, and transformed data.
- ✅ Improved data consistency and quality.
- ✅ Development of a systematic ETL workflow.
- ✅ Separation of data processing into independent layers.
- ✅ Creation of analytics-ready datasets.
- ✅ Better understanding of modern data warehousing concepts.

---

## 🚀 Key Learnings

- Understanding modern data warehouse architecture.
- Working with Bronze, Silver, and Gold layers.
- Understanding ETL pipeline development.
- Data cleaning and transformation techniques.
- Organizing and maintaining data engineering projects.

---

## 👩‍💻 Author

**Divyashree S A**

GitHub: [@dcodeforge](https://github.com/dcodeforge)

---

⭐ If you find this project useful, consider giving the repository a star!