# Loan Management System (SQL)

## 🎯 Objective
Design and implement a SQL-based loan management system to track loans, automate interest calculations, and generate reports to identify high-risk accounts.

## 🛠 Tools Used
SQL (MySQL or PostgreSQL), CSV for sample data, basic scripting for data load

## 🔧 What I built
- Database schema to store customers, loans, payments, and schedules  
- ETL process (sample CSV import) to load 1,000+ loan records into the database  
- Stored procedures and scheduled jobs to compute interest automatically (reducing manual processing by ~40%)  
- Reporting views to show overdue loans, repayment progress, and high-risk customers

## ✅ Key SQL components (examples to include in your repo)
- `schema.sql` — table definitions for `customers`, `loans`, `payments`  
- `interest_proc.sql` — stored procedure to compute interest and update balances  
- `report_views.sql` — views for summary and overdue reports  
- `sample_data.csv` — anonymized sample loan records

## 📈 Example insights
- Identified 12% of loans as at-risk based on payment lateness and high outstanding balances  
- Automated calculations freed up analyst time previously spent on manual spreadsheets

## 📂 Files to upload
- loan_management/schema.sql  
- loan_management/interest_proc.sql  
- loan_management/report_views.sql  
- loan_management/sample_data.csv
