# 🏥 Nurse-Scheduler-Insight: Clinical Decision Support System (CDSS)

**Nurse-Scheduler-Insight** is a Python-based analytical tool designed to optimize nursing management by bridging the gap between clinical operations and data science. This project simulates a **Clinical Decision Support System (CDSS)** aimed at preventing staff burnout and ensuring high-quality patient care through data-driven scheduling.

## 🚀 Key Features

* **Burnout Risk Analysis:** Automatically identifies healthcare professionals exceeding the 40-hour weekly limit to ensure workplace safety and mental well-being.
* **Academic Competency Mapping:** Analyzes the distribution of Bachelor’s vs. Master’s degrees across different departments to assess team clinical expertise.
* **Smart Shift Candidate Selection:** Uses multi-criteria filtering (Department + Education + Current Workload) to find the most eligible senior staff for critical units like the ICU.
* **Data Integrity & Cleaning:** Implements robust error handling and data cleaning to manage missing values and ensure the system remains stable during analysis.

## 🛠️ Technologies Used

* **Python 3.x**
* **Pandas:** For high-performance data manipulation and clinical metrics analysis.
* **CSV:** For structured storage of healthcare personnel records.

## 📊 Dataset Overview

The project utilizes a synthetic dataset containing 100 professional profiles with the following attributes:
* **nurse_id**, **name**, **education_level** (Bachelor's / Master's), **department** (ICU, ER, Cardiology, etc.), **weekly_hours**, and **experience_years**.

## 💻 Technical Implementation

The analysis is performed through organized code blocks that handle:
1. **Staff Filtering**: Isolating at-risk personnel based on workload.
2. **Grouping & Aggregation**: Summarizing education levels by clinical department.
3. **Conditional Selection**: Identifying shift leaders using specific clinical requirements.

## 🎯 Project Goal

As a student of both **Nursing** and **Computer Programming**, I developed this project to demonstrate how software can solve real-world administrative challenges in hospitals. This tool serves as a foundation for more advanced, AI-driven hospital management systems.

## Disclaimer
​This project is for educational and portfolio purposes only. It is not intended for use in clinical environments or for real patient data processing. The developer is not responsible for any decisions made based on the outputs of this software.