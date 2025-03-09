# Operator Case Study – Data Analyst Challenge

## 📌 Overview
This project addresses the **RCM Data Analyst Challenge: Closed Encounters Analysis**. It involves comparing two datasets:
1. **Client’s EHR Closed Encounters** – A list of closed encounters recorded in the electronic health records (EHR).
2. **Imported Closed Encounters** – A list of encounters that were successfully imported into the Normandy system.

The goal is to identify missing encounters, analyze possible reasons for missing data, and summarize findings.

---

## 📂 Project Structure
📁 Operator_Case_Study_Problem/ │── 📄 README.md # Project Documentation │── 📂 data/ # Sample data files (EHR & Imported Encounters) │── 📂 notebooks/ # Jupyter notebooks for EDA & analysis │── 📂 scripts/ # Python scripts for automation │── 📄 augmidex_assessment_task.py # Main script for data processing & analysis │── 📄 requirements.txt # Dependencies & Python libraries │── 📊 results/ # Outputs (CSV reports, visualizations, etc.)


---

## 🔍 Tasks & Approach
### **Task 1: Identifying Missing Encounters**
- Extract unique encounters using **Patient Name, Date of Service, and Rendering Provider**.
- Compare datasets to determine which encounters are missing.
- Store the list of missing encounters in a structured format.

### **Task 2: Investigating the Causes**
- Analyze trends in missing encounters based on:
  - **Providers** (Which providers have the most missing encounters?)
  - **Procedure Codes** (Are certain medical procedures more likely to be missing?)
  - **Time Periods** (Are missing encounters clustered in specific months?)
- Summarize findings and suggest potential causes.

---

## 🚀 Implementation
### **Technologies Used**
- Python 🐍
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualization
- Jupyter Notebook for exploration
- CSV processing for structured reports

### **Key Features**
✅ **Data Cleaning & Preprocessing** – Standardizes column names, removes duplicates, and handles missing values.  
✅ **Missing Encounter Identification** – Compares datasets to extract missing encounters.  
✅ **Exploratory Data Analysis (EDA)** – Identifies patterns in missing encounters.  
✅ **Summary Reports & Export** – Generates CSV reports & visualizations for key findings.  

---

## 📊 Results & Findings
- **X%** of encounters were missing from the imported dataset.
- The most affected providers were **Provider A, Provider B**, etc.
- Certain **CPT codes** were more likely to be missing.
- **Time-based trends** showed peak missing data in certain months.

---
📌 Future Enhancements
🔹 Automate data ingestion from databases.
🔹 Implement advanced anomaly detection techniques.
🔹 Use Machine Learning for predictive analysis.

