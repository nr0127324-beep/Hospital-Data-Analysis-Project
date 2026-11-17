# Hospital Data Analysis and Performance Management System

## Project overview
This beginner-friendly portfolio project analyzes 1,000 synthetic hospital patient records to explore admissions, department activity, treatment costs, length of stay, payment methods, and patient satisfaction.

> **Data note:** This dataset is synthetic and for learning/portfolio practice only. It is not real patient information and must not be used for clinical decisions.

## Tools
- Excel: inspect and summarize the CSV
- Python (Pandas, NumPy, Matplotlib): clean and explore the data
- MySQL: store records and answer business questions with SQL
- Power BI: build an interactive dashboard

## Dataset
`Dataset/hospital_data_1000_rows.csv`

It contains 1,000 rows and 13 columns:
Patient_ID, Name, Age, Gender, Department, Admission_Date, Discharge_Date, Diagnosis, Treatment_Cost, Doctor, Stay_Days, Payment_Mode, Satisfaction.

Some fields intentionally contain missing values so data-cleaning steps can be practiced.

## Project workflow
1. Inspect the CSV in Excel.
2. Clean missing values and check duplicates with the Python script in `Python/`.
3. Create the MySQL database and table using `SQL/hospital_analysis.sql`.
4. Import the cleaned CSV into MySQL.
5. Run the analysis queries in the SQL script.
6. Connect Power BI to MySQL and create KPI cards, charts, and slicers.
7. Add dashboard screenshots and write findings based on your actual results.

## Folder guide
- `Dataset/` - original synthetic CSV
- `Excel/` - save your Excel workbook here
- `Python/` - Python cleaning and analysis script
- `SQL/` - database setup and analysis queries
- `PowerBI/` - save your `.pbix` dashboard here
- `Screenshots/` - save dashboard images here

## Important
Do not claim example figures as findings. Calculate all final metrics from the dataset and document the actual results.
