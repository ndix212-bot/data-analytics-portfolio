# Data Analytics & ETL Portfolio

Welcome to my data portfolio. This repository contains end-to-end Python and SQL pipelines designed to clean, audit, and structure disorganized business data into production-ready formats and relational databases.

---

## Repository Structure

Based on the project files layout, here is where everything lives:
*   `README.md` - Portfolio directory and project documentation (this file).
*   `corporate_finance_etl_pipeline.ipynb` - Python notebook containing the high-level corporate finance currency normalization, auditing, and SQLite pipeline.
*   `ecommerce_data_cleaning.ipynb` - Python notebook containing the source ETL code for auditing and deduplicating retail transaction logs.
*   `cleaned_ecommerce_sales_data.csv` - The final, production-ready, clean dataset exported by the e-commerce pipeline.

---

## Featured Pipelines

### 1. Corporate Finance ETL & M&A Due Diligence
*   **Notebook:** `corporate_finance_etl_pipeline.ipynb`
*   **Tech Stack:** Python (Pandas), SQL (SQLite), Excel
*   **Core Functions:** 
    *   Normalizes multi-currency financial records (USD/EUR) using explicit exchange logic.
    *   Standardizes chaotic fiscal period strings and strips embedded footnote anomalies.
    *   Features an automated data integrity audit engine comparing reported financials against calculated metrics.
    *   Automatically provisions structured tables in a local SQLite relational database (`corporate_financials.db`).

### 2. E-Commerce Retail Sales Data Cleaner
*   **Notebook:** `ecommerce_data_cleaning.ipynb`
*   **Production Output:** [View Cleaned E-Commerce Dataset (CSV)](cleaned_ecommerce_sales_data.csv)
*   **Tech Stack:** Python (Pandas)
*   **Core Functions:** 
    *   Audits and cleans broken retail transaction spreadsheets.
    *   Deduplicates transaction logs and strips corrupt non-printing hidden characters from text fields.
    *   Standardizes timestamp fields and handles missing numerical values safely.

---

## Skills Demonstrated
*   **Data Wrangling:** Handling missing values, structural anomalies, and text formatting with Python.
*   **Financial & Business Logic:** Currency normalization, ledger auditing, and fiscal tracking.
*   **Database Engineering:** Moving flat data streams cleanly into relational SQL environments.
