🏥 Novartis Hospital Administration Analysis using Microsoft Excel
📌 Project Overview

This project focuses on analyzing hospital administration data to identify the major factors influencing patient readmissions and provide actionable insights for improving patient care and reducing healthcare costs.

The analysis was performed using Microsoft Excel, leveraging advanced Excel functionalities such as data cleaning, formulas, Pivot Tables, Pivot Charts, dashboards, statistical analysis, and interactive slicers.

The project is based on a real-world healthcare case study where the hospital administration aims to reduce unnecessary readmissions by understanding patient demographics, diagnoses, medication usage, hospital stay patterns, and healthcare utilization. The project addresses 20 analytical questions (10 Basic + 10 Medium) from the case study.

🎯 Problem Statement

Hospital readmissions increase operational costs, reduce resource availability, and may indicate gaps in patient care. The objective of this project is to analyze hospital admission records to identify patterns associated with readmission and recommend data-driven interventions to improve healthcare quality and operational efficiency.

🎯 Project Objectives
Analyze patient demographics and healthcare utilization.
Identify factors influencing hospital readmissions.
Study diagnosis and medication patterns.
Evaluate hospital resource utilization.
Build an interactive executive dashboard.
Generate actionable business recommendations for hospital administrators.
🏥 Business Scenario

The hospital administration has observed an increase in patient readmission rates, leading to:

Increased treatment costs
Reduced hospital capacity
Poor patient outcomes
Operational inefficiencies
Lower healthcare quality indicators

The management requires analytical insights to support better decision-making and targeted patient care strategies.

📂 Dataset Information

Dataset Source

Hospital Administration Dataset (Kaggle)

The dataset contains patient-level healthcare records, including:

Demographics
Medical specialties
Diagnosis codes
Laboratory procedures
Medications
Previous hospital visits
Diabetes medication indicators
Readmission status

Key attributes include:

Encounter ID
Patient ID
Age
Gender
Race
Weight
Medical Specialty
Time in Hospital
Number of Lab Procedures
Number of Medications
Number of Diagnoses
Diabetes Medication
Medication Change
Readmitted
X1–X25 Medication Indicators
🛠 Tools & Technologies Used
Microsoft Excel
Power Query (Data Cleaning)
Excel Tables
Pivot Tables
Pivot Charts
Conditional Formatting
Slicers
Lookup Functions
IF / IFS / SWITCH Functions
COUNTIFS
AVERAGEIFS
Statistical Functions
Dashboard Design
Data Visualization
📊 Data Cleaning Process

The dataset underwent comprehensive preprocessing before analysis.

Data Cleaning Steps
Removed duplicate records after validating unique encounter information.
Handled missing values appropriately.
Retained weight data and analyzed only valid records where required.
Standardized inconsistent categorical values.
Grouped diagnosis codes into clinically meaningful diagnosis categories.
Created age groups for demographic analysis.
Created Emergency Visit bins.
Created Medication Adjustment Score.
Created Medication Adjustment Level.
Created Readmission Flag.
Classified medication indicators.
Validated data integrity before visualization.
📈 Feature Engineering

Several new analytical variables were created to enhance insights.

Created Columns
Diagnosis Category (DiagType)
Medication Adjustment Score
Medication Adjustment Level
Readmission Flag
Emergency Visit Categories
Age Groups
Weight Categories

These derived fields enabled advanced analyses beyond the original dataset.

📋 Project Requirements

The case study required solving:

Basic Analysis (10 Questions)

Examples include:

Readmission trends by age
Average hospital stay by specialty
Emergency visits vs readmissions
Diabetes readmission analysis
Medication change analysis
Lab procedures vs readmission
Race and gender comparison
Weight category analysis
Medication impact on hospital stay
Outpatient visits vs readmission
Medium Analysis (10 Questions)

Examples include:

Comorbidity analysis
Demographic treatment analysis
Diagnosis-based healthcare utilization
Medication prescribing patterns
Weight × Diagnosis interaction
Diabetic medication effectiveness
Readmission risk analysis
Executive healthcare recommendations

All required analytical questions from the case study were addressed using Excel-based analytical techniques.

📊 Dashboard Overview

An interactive executive dashboard was developed to summarize key findings.

Dashboard Features
KPI Cards
Total Patients
Readmission Rate
Average Length of Stay
Average Medications
Average Diagnoses
Average Medication Adjustment Score
Interactive Charts
Patient Distribution by Age
Readmission Distribution
Readmission by Diagnosis
Weight vs Readmission
Medication Adjustment vs Readmission
Average Length of Stay by Diagnosis
Medical Specialty Distribution
Emergency Visits vs Readmission
Interactive Slicers
Age
Diagnosis Category
Readmission Status

These slicers dynamically update all charts and KPI cards, enabling interactive exploration.

📌 Key Insights

The analysis revealed several important findings:

Elderly patients (particularly ages 60–80) represented the largest patient population.
Chronic disease diagnosis categories contributed significantly to hospital readmissions.
Patients requiring higher medication adjustments showed increased readmission likelihood.
Weight categories combined with diagnosis types helped identify high-risk patient groups.
Previous emergency visits were associated with greater readmission risk.
Certain medical specialties experienced longer average hospital stays, indicating higher resource utilization.
Diabetes medication patterns highlighted opportunities for improving discharge planning and follow-up care.
💡 Business Recommendations

Based on the analysis, the following recommendations are proposed:

Implement targeted follow-up programs for high-risk patients.
Strengthen medication reconciliation before discharge.
Improve diabetes management and patient education.
Prioritize monitoring for patients with frequent emergency visits.
Optimize discharge planning for patients with multiple diagnoses.
Allocate resources efficiently to specialties with longer hospital stays.
Develop predictive monitoring strategies for patients at high risk of readmission.
Enhance preventive care programs for elderly patients.
⚠ Challenges Faced

During the project, several practical data challenges were encountered:

Large number of missing values in the Weight column.
Duplicate Encounter IDs requiring validation.
Inconsistent diagnosis code formats.
Anonymous medication indicators (X1–X25) without descriptive names.
Medication-related variables mixed with laboratory result indicators.
Absence of patient satisfaction data, preventing the completion of one requested analysis.
No date field available for seasonal trend analysis.
Complex diagnosis classification requiring ICD-based grouping.

These challenges were resolved through appropriate preprocessing, feature engineering, and analytical assumptions while preserving data quality.

🚀 Future Improvements

Future enhancements to this project could include:

Predictive readmission models using machine learning.
Power BI dashboard implementation.
SQL integration for automated reporting.
Real-time hospital monitoring dashboards.
Patient segmentation using clustering techniques.
Financial impact analysis of avoidable readmissions.
Integration of patient satisfaction and mortality datasets.
Automated ETL pipelines using Power Query or Python.
📚 Learning Outcomes

This project strengthened practical skills in:

Data Cleaning
Data Preparation
Exploratory Data Analysis (EDA)
Healthcare Analytics
Pivot Tables
Dashboard Design
KPI Development
Data Visualization
Business Problem Solving
Executive Reporting
Analytical Thinking
📁 Repository Structure
Hospital-Administration-Analysis/
│
├── Hospital Administration Analysis.xlsx
├── DACS08 - Hospital Administration Analysis.pdf
├── README.md
└── Dashboard_Screenshots/
🎯 Conclusion

This project demonstrates how Microsoft Excel can be effectively used for end-to-end healthcare analytics, from data cleaning and exploratory analysis to dashboard development and business recommendations. By analyzing patient demographics, diagnosis patterns, medication usage, and healthcare utilization, the project provides actionable insights that can help hospital administrators improve patient outcomes, reduce avoidable readmissions, and optimize resource allocation. The resulting interactive dashboard serves as a practical decision-support tool for monitoring hospital performance and identifying opportunities for continuous improvement.
