🏥 Hospital Management System – Data Analytics Project
📌 Overview

This project analyzes hospital operations data to generate actionable insights on revenue, patient trends, doctor performance, and payment efficiency.

The solution combines SQL, Python, and Power BI to build a complete data analytics pipeline and an interactive dashboard.

🎯 Objectives
Analyze hospital revenue and financial performance
Track patient and appointment trends
Evaluate doctor workload and specialization demand
Identify inefficiencies in billing and payment systems
Build an interactive dashboard for decision-making
🧩 Data Model

The project is built on a relational database with the following tables:

Patients
Doctors
Appointments
Treatments
Billing
🔗 Relationships:
One patient → multiple appointments
One doctor → multiple appointments
Each appointment → one treatment
Each treatment → one billing record
⚙️ Tech Stack
SQL → Database design & queries
Python (Pandas, NumPy) → Data cleaning & preprocessing
Power BI → Data visualization & dashboard
🔄 ETL Pipeline
1. Extraction
Data imported from CSV files
2. Transformation
Data cleaning (missing values, formatting)
Standardization of categories (payment status, specialization)
Feature engineering (KPIs, aggregates)
3. Loading
Data stored in SQL database
Connected to Power BI for visualization
📊 Dashboard Insights
🔹 Key Metrics
Total Revenue: $551.25K
Total Appointments: 200
Total Patients: 50
Average Treatment Cost: $2.73K
Payment Success Rate: 32%
🔍 Key Findings
💰 Revenue Trends
Revenue fluctuates monthly
Indicates inconsistent demand or scheduling
💳 Payment Analysis
Only 32% successful payments
High number of failed and pending transactions

👉 Major revenue leakage identified

👨‍⚕️ Doctor Performance
Uneven distribution of appointments
Some doctors are overutilized
🏥 Treatment Costs
MRI is the most expensive
ECG is the least expensive
📅 Appointment Trends
Peak around mid-year
Decline in later months
🧬 Specialization Insights
Pediatrics dominates
Oncology has lowest demand
🏥 Insurance Analysis
Revenue concentrated among few providers
Payment delays vary across providers
🚨 Key Problems Identified
Low payment success rate
Revenue instability
Uneven doctor workload
Dependency on limited insurance providers
💡 Recommendations
Improve billing and payment tracking systems
Optimize doctor scheduling and workload distribution
Expand high-demand specializations
Use predictive analytics for demand forecasting
