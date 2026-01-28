# Data-Quality-Checker-QC

# Project Description

This project is an automated Data Quality Checker and Market Research Data Processing Pipeline built using Python and Excel.  
It validates, cleans, and prepares raw Excel/CSV datasets for analysis by applying standard data quality checks, transformations, and summary reporting.
The solution is designed to work with any structured Excel or CSV file and generates a comprehensive QC report along with clean, analysis-ready data.
This project simulates real-world data processing workflows used in market research, analytics, and business operations teams.

---

## Key Features

- Reads Excel (.xlsx) and CSV (.csv) files
- Automated Data Quality Checks:
- Total rows & columns
- Total NULL values
- Column-wise NULL count & percentage
- Duplicate row detection
- Empty rows & empty columns
- Data type validation
- Numeric outlier detection (IQR method)
- Generates a multi-sheet Excel QC Report
- Reusable for different datasets with minimal changes
- Beginner-friendly and easy to extend

---


---

## Tech Stack

- Python
- Pandas
- OpenPyXL
- Excel (Input & Output)

---

## How It Works

1. Load Excel or CSV data using Pandas
2. Perform automated data quality validations
3. Calculate completeness, duplication, and outliers
4. Generate structured QC metrics
5. Export results to a multi-sheet Excel report

---

## QC Report Sheets

| Sheet Name | Description |
|-----------|------------|
| Summary | Overall dataset metrics |
| Missing Values | Column-wise NULL count |
| Data Types | Column data types |
| Outliers | Numeric outlier count |
| Duplicates | Duplicate row summary |

---

## How to Run

```bash
pip install pandas openpyxl
python qc_checker.py

## 🗂 Project Structure

