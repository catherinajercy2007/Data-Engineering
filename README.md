# Data Engineering Internship Project – Railway Data Analysis

## Overview
This project was completed as part of my **Data Engineering Internship at Cognifyz Technologies**.  
It demonstrates a complete data engineering workflow, including data ingestion, cleaning, transformation, analysis, and visualization using Python.

The objective of this project is to analyze railway operational data and extract meaningful insights through structured data processing techniques.

---

## Dataset
**File:** `Railway_info.csv`  
**Records:** 11,113  
**Attributes:**  
- Train_No  
- Train_Name  
- Source_Station_Name  
- Destination_Station_Name  
- days  

The dataset represents train operations across various source and destination stations along with operating days.

---

## Project Workflow

### 1. Data Ingestion & Exploration
- Loaded the dataset using Pandas
- Inspected structure, data types, and missing values
- Verified dataset consistency and completeness

### 2. Data Cleaning & Standardization
- Checked and confirmed absence of duplicate records
- Standardized station and train name formats
- Corrected inconsistent day values and typographical errors

### 3. Data Transformation & Feature Engineering
- Created a `Train_Type` column (EMU, Express, Superfast, Special, Other)
- Generated a `Route` feature combining source and destination stations
- Categorized train operations based on frequency (Daily / Weekly)

### 4. Data Aggregation & Analysis
- Identified busiest source and destination stations
- Analyzed day-wise train frequency patterns
- Evaluated popular railway routes and operational trends

### 5. Data Visualization
- Bar charts for day-wise train distribution
- Top source and destination stations visualization
- Train type distribution analysis using Matplotlib

---

## Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, Matplotlib  
- **Environment:** Google Colab  

---

## Key Insights
- Major railway hubs such as CST-Mumbai, Sealdah, Chennai Beach, and Howrah Junction dominate train operations
- Weekend and daily commuter services account for a significant portion of railway traffic
- Suburban EMU routes show highly symmetrical source-destination patterns
- Data enrichment enabled more meaningful operational insights

---

## Files Included
- `Cognify_Data_Engineering_Task.ipynb` – Complete notebook with code and outputs
- `Cognify_Data_Engineering_Task_Report.pdf` – Final report with analysis and visualizations
- `Railway_info.csv` – Input dataset
- `README.md` – Project documentation

---

## Conclusion
This project reflects a structured data engineering approach, focusing on data quality, transformation, and analytical readiness.  
The workflow and outputs are designed to support downstream analytics and reporting use cases.

---

## Author
**Catherina Jercy**  
Data Engineer Intern  
Cognifyz Technologies
