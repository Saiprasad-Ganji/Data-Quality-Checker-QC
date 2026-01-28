# Data-Quality-Checker-QC
This project is an automated Data Quality Checker and Market Research Data Processing Pipeline built using Python and Excel.
It validates, cleans, and prepares raw Excel/CSV datasets for analysis by applying standard data quality checks, transformations, and summary reporting.
The solution is designed to work with any structured Excel or CSV file and generates a comprehensive QC report along with clean, analysis-ready data.
This project simulates real-world data processing workflows used in market research, analytics, and business operations teams.

Key Features
Reads Excel (.xlsx) and CSV (.csv) files
Automated Data Quality Checks
Total rows & columns
Total NULL values
Column-wise NULL count & percentage
Duplicate row detection
Empty rows & empty columns
Data type validation
Numeric outlier detection (IQR method)
📊 Generates a multi-sheet Excel QC Report
🔁 Reusable for different datasets with minimal changes
🧠 Beginner-friendly and easy to extend

🗂 Project Structure

Market-Research-Data-QC/
│
├── data/
│   └── Airline_Sample.xlsx
│
├── qc_checker.py
├── QC_Report.xlsx
└── README.md

🛠 Tech Stack

Python
Pandas
OpenPyXL
Excel (Input & Output)

⚙️ How It Works

Load Excel or CSV data using Pandas
Perform automated data quality validations
Calculate completeness, duplication, and outliers
Generate structured QC metrics
Export results to a multi-sheet Excel report

📊 QC Report Sheets

Sheet Name	Description
Summary	Overall dataset metrics
Missing Values	Column-wise NULL count
Data Types	Column data types
Outliers	Numeric outlier count
Duplicates	Duplicate row summary

▶️ How to Run

pip install pandas openpyxl
python qc_checker.py

The output file QC_Report.xlsx will be generated in the project directory.

📌 Sample Metrics Generated

Total Rows
Total Columns
Total NULL Values
Duplicate Rows
NULL Percentage per Column
Outlier Counts

🧪 Use Cases

Market Research data validation
Survey data cleaning
Business reporting & MIS
Data analyst quality checks
Pre-analysis data preparation

🌱 Future Enhancements

QC PASS / FAIL logic with thresholds
Config-driven rules (YAML / Excel)
Email alerts for QC failures
Streamlit dashboard
Automated scheduling

🧠 What This Project Demonstrates

Practical data quality concepts
Real-world Excel & Python integration
Business-oriented data validation
Clean, reusable analytics code

📄 License

This project is for learning and portfolio purposes.


🔥 Short GitHub Repo Description (use this line)

Automated Data Quality Checker and Market Research data processing pipeline using Python and Excel.
