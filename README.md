# Data Cleaning and Analysis of Retail Sales Dataset (Excel)

## Project Overview
This project focuses on cleaning, standardizing, and preparing a retail sales dataset for reliable analysis using Microsoft Excel. The dataset initially contained common real-world data quality issues such as duplicates, missing values, inconsistent formatting, and incorrect data types.

The objective was to transform raw transactional data into a structured, analysis-ready dataset that can support accurate business insights and downstream analytics work.

---

## Dataset Description
The dataset contains **31 retail transaction records** with the following key fields:

- Date of Sale  
- Customer ID  
- Customer Name  
- Region  
- Product  
- Quantity  
- Price per Unit  
- Rating  

---

## Data Cleaning Process

### 1. Data Formatting
- Auto-fitted rows and columns for full visibility and readability.
- Standardized the worksheet layout to reduce visual ambiguity.

### 2. Duplicate Removal
- Identified and removed duplicate transaction records.
- Reduced dataset size from 31 rows to **28 unique records**.

### 3. Handling Missing Values
- Detected blank cells in the `Region` column.
- Replaced missing values with `Null` rather than guessing or deleting records, preserving data integrity.

### 4. Error Correction
- Used Find and Replace to correct invalid values.
- Replaced `inf` values in the *Price per Unit* column with `0` to maintain numerical consistency.

### 5. Data Type Validation
- Corrected incorrect data types across columns.
- Ensured date, numeric, and text fields were properly assigned for analysis.

### 6. Conversion to Structured Table
- Converted the cleaned dataset into an Excel Table.
- Enabled easier filtering, sorting, and future analytical use.

### 7. Data Validation
- Verified that all columns were consistent, complete, and ready for analysis.

---

## Final Output
- A fully cleaned and validated retail sales dataset.
- Suitable for further analysis, reporting, or visualization in tools such as Power BI or SQL-based systems.

---

## Tools Used
- Microsoft Excel

---

## Skills Demonstrated
- Data cleaning and preprocessing  
- Handling duplicates and missing values  
- Data validation and standardization  
- Preparing raw data for business intelligence workflows  
- Attention to data quality and integrity  

---

## Notes for Reviewers
This project emphasizes **data quality fundamentals**, which are critical in analytics engineering and business intelligence workflows. No dashboards or visualizations were created, as the primary focus was dataset reliability and preparation.

## 📜 License
This project is made available under the MIT License.  
Feel free to use, modify, and redistribute it with proper credit.

## 👤 About Me
Hi. My name is Samuel Ayomide Makanjuola.  
I am a data enthusiast with growing expertise in Analytics Engineering, BI Analysis, Full Stack Data Analysis, data engineering, analytics, and data modelling.  
I enjoy building practical data solutions that transform raw information into insights that support real business decisions.

If you are interested in collaborating or exploring opportunities with me, feel free to reach out.  
I am open to roles, projects, and partnerships within the data space.
