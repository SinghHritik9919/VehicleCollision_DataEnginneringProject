# 🚗 Vehicle Collision Analysis  

## 📌 Project Overview  
The **Vehicle Collision Analysis** project aims to analyze collision data from four major U.S. cities:  
- **Chicago**  
- **Austin**  
- **New York**  
- **Montgomery**  

This project involves data profiling, extraction, transformation, and visualization to uncover patterns, trends, and insights related to vehicle collisions.

## 📂 Data Sources  
The dataset consists of collision records from the above cities, obtained in **CSV/TSV** format.

## 🔄 Workflow  

### 1️⃣ Data Profiling  
- **Tool Used**: *Alteryx*  
- **Purpose**: Perform an initial assessment of data quality, detect missing values, and understand the structure of datasets.  

### 2️⃣ Data Ingestion  
- **Tool Used**: *Azure Data Factory (ADF)*  
- **Process**:  
  - Each city's data is ingested individually from **TSV/CSV** files.  
  - The data is loaded into Snowflake as raw tables.  

### 3️⃣ Data Transformation & Integration  
- **Tool Used**: *Talend*  
- **Process**:  
  - Cleanse and standardize datasets.  
  - Handle missing, inconsistent, or erroneous data.  
  - Combine data from all four cities into a **single unified table** in Snowflake.  

### 4️⃣ Data Visualization  
- **Tools Used**: *Power BI & Tableau*  
- **Purpose**:  
  - Create interactive dashboards and reports.  
  - Analyze trends, accident hotspots, and potential causes.  

## 🛠️ Technologies Used  
- **ETL & Data Processing**: Alteryx, Azure Data Factory, Talend  
- **Database & Storage**: Snowflake  
- **Visualization**: Power BI, Tableau  

## 🚀 Future Enhancements  
- Implement **real-time** data ingestion.  
- Perform **predictive analytics** on collision data.  
- Enhance data granularity by integrating additional features like weather conditions and traffic density.  

## 👤 Author  
**Hritik Singh**  
- **GitHub**: [SinghHritik9919](https://github.com/SinghHritik9919)  
- **LinkedIn**: [Hritik Singh](https://www.linkedin.com/in/hritik-singh9919)  

