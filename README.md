# Agriculture Sector Analytics & Forecasting Pipeline (AWS/Snowflake) ☁️

## 1. Overview
Designed and built a scalable cloud-based ELT (Extract, Load, Transform) data pipeline to integrate disparate datasets (Crop Production, Weather, Soil Data). The goal was to provide a unified data mart for analyzing agricultural trends and forecasting crop yields.

### 🎯 Goal
To consolidate multiple data sources into a centralized, clean data warehouse (Snowflake) to enable advanced analytical reporting and predictive modeling for better resource allocation.

## 2. Tools & Technologies (The Modern Data Stack)
- **Cloud/Storage:** **AWS S3** (Data Ingestion/Staging)
- **Data Warehousing:** **Snowflake** (Storage, Scalable Compute)
- **Transformation:** **Advanced SQL** (Window Functions, CTEs)
- **Business Intelligence:** Power BI / Tableau
- **Data:** Multiple CSV files (Crop Production, Weather, Soil)

## 3. Key Actions / Process (The ELT Pipeline)

### I. Data Ingestion (E & L)
- **AWS S3 Staging:** Uploaded all raw data files to S3 buckets, creating a scalable staging area.
- **Snowflake Integration:** Used Snowflake's **COPY INTO** command to rapidly load all raw data from S3 directly into staging tables.

### II. Data Transformation (T)
- **SQL Modeling:** Executed complex SQL transformations using **CTEs (Common Table Expressions)** to clean data, join tables (e.g., production records to weather stations), and resolve inconsistencies.
- **Data Mart Creation:** Built a final, aggregated analytical table/view optimized for BI reporting, ensuring fast query performance for downstream consumers.

### III. BI Delivery
- Connected Power BI/Tableau directly to the **Snowflake warehouse** to visualize trends (e.g., correlation between rainfall and yield) and build interactive dashboards.

## 4. Key Achievements & Results
- **Scalability:** Successfully migrated the entire analytical process from local files to a scalable cloud data warehouse, eliminating local data storage bottlenecks.
- **Integration:** Successfully integrated and modeled three highly disparate datasets (production, weather, soil), allowing for **cross-functional analysis** previously impossible.
- **Technical Depth:** Demonstrated expertise in the modern data stack (S3 $\rightarrow$ Snowflake $\rightarrow$ BI), a highly sought-after skill set in the market.

## 5. View Project
- **Snowflake SQL Proof:** `AgricultureDataP - Snowflake.html` (Query history and results available in this repo)
- **Dashboard Preview:** `AgricultureDataFinal.pbix` (Dashboard visualization)
