# RetainX

# Project phases

PHASE 0 → Project Planning  
PHASE 1 → Environment Setup  
PHASE 2 → Dataset Understanding  
PHASE 3 → Data Cleaning  
PHASE 4 → Exploratory Data Analysis  
PHASE 5 → Feature Engineering  
PHASE 6 → Statistical Analysis  
PHASE 7 → Data Warehouse / Star Schema  
PHASE 8 → Power BI + DAX  
PHASE 9 → Executive Dashboard  
PHASE 10 → Documentation + Portfolio  

# Architecture
RetainX/  
│  
├── data/  
│   ├── rawdata/  
│   │   └── employee_attrition_dataset_10000.csv  
│   │    
│   └── processed/    
│       └── retainx_hr_1000.csv  
│   
├── notebooks/  
│   ├── 01_data_setup.ipynb  
│   ├── 02_data_cleaning.ipynb  
│   ├── 03_eda.ipynb  
│   ├── 04_feature_engineering.ipynb  
│   └── 05_statistical_analysis.ipynb  
│  
├── src/  
│   ├── cleaning.py  
│   └── metrics.py  
│  
├── reports/  
│   └── figures/  
│  
├── power_bi/  
│   └── RetainX_HR_Analytics.pbix  
│  
├── requirements.txt  
├── .gitignore  
└── README.md  
### Phase 3 — Exploratory Data Analysis

3.1 Workforce composition  
Employees by:  
├── Department  
├── Job Role  
├── Gender  
├── Job Level  
└── Age group  
3.2 Attrition  
Overall attrition  
       ↓  
Department attrition  
       ↓  
Job-role attrition  
       ↓  
Overtime attrition  
       ↓  
Satisfaction attrition  
       ↓  
Tenure attrition  
3.3 Compensation  
Salary distribution  
       ↓  
Salary by Department  
       ↓  
Salary by Job Role  
       ↓  
Salary vs Attrition  
3.4 Career progression  
Years at Company  
Years in Current Role  
Years Since Last Promotion  
       ↓  
Attrition  
3.5 Workload  
Overtime  
Project Count  
Average Weekly Hours  
Absenteeism  
       ↓  
Attrition  
3.6 Employee experience  
Job Satisfaction  
Work-Life Balance  
Manager Relationship  
Work Environment Satisfaction  
Job Involvement  
       ↓  
Attrition  

These are necessary because they directly support our business objective.  

Phase 4 — Visualization  


Chart 1 — Attrition distribution  

Bar chart:

Attrition  
│
├── Yes  
└── No    
Chart 2 — Department attrition  
Department  
     ↓  
Attrition %  
  
Bar chart.  

Chart 3 — Job-role attrition  
Job Role  
   ↓  
Attrition %  

Bar chart.  

Chart 4 — Salary distribution  

Here your original violin plot idea is useful.  

Salary  
  │  
  ├── Department A  
  ├── Department B  
  ├── Department C  
  └── ...  

Violin plot = useful.  

Chart 5 — Overtime vs attrition  
Overtime  
   │  
   ├── Yes → Attrition %  
   └── No  → Attrition %  
Chart 6 — Satisfaction vs attrition  
Job Satisfaction  
       ↓  
Attrition %  
Chart 7 — Tenure vs attrition  
Years at Company  
       ↓  
Attrition %  
Chart 8 — Correlation heatmap  

This is useful for identifying relationships among:  

Age  
Income  
Tenure  
Promotion  
Satisfaction  
Workload  
Performance  
Absenteeism  
