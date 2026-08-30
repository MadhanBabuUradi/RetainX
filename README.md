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
                         RAW DATA
                            │
                            ▼
                  ┌────────────────────┐
                  │   Python / Pandas  │
                  │   Data Cleaning    │
                  └─────────┬──────────┘
                            │
                            ▼
                  ┌────────────────────┐
                  │    Data Quality    │
                  │     Validation     │
                  └─────────┬──────────┘
                            │
                            ▼
                  ┌────────────────────┐
                  │ Feature Engineering│
                  │      NumPy         │
                  └─────────┬──────────┘
                            │
              ┌─────────────┴─────────────┐
              ▼                           ▼
     ┌──────────────────┐        ┌──────────────────┐
     │ EDA / Statistics │        │  BI Data Model   │
     │ Matplotlib       │        │   Star Schema    │
     │ Seaborn          │        └────────┬─────────┘
     └──────────────────┘                 │
                                          ▼
                              ┌─────────────────────┐
                              │      Power BI       │
                              │ Power Query + DAX   │
                              └──────────┬──────────┘
                                         │
                                         ▼
                              ┌─────────────────────┐
                              │ Executive Dashboard │
                              └──────────┬──────────┘
                                         │
                                         ▼
                                BUSINESS INSIGHTS
