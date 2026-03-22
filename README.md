# Heart Failure Prediction — Power BI Analysis

## Overview

End-to-end Business Intelligence solution built in **Microsoft Power BI** for analysing clinical and demographic factors associated with heart failure. The project covers the full BI pipeline — from data cleaning and modelling to interactive dashboards — answering **16 research questions** on patient survival, risk factors and demographic patterns.

> Developed as part of the **Business Intelligence Tools II** course, MSc in Artificial Intelligence & Data Analytics.

---

## Dashboards

### KPI Overview
![KPI Overview](ac4de58b-7e61-44d8-9c93-2fc1b5dea0e8.jpg)

### Correlation Analysis Heatmap
![Correlation Analysis](42eebdbe-0b19-42ac-9b00-5f450d11a781.jpg)

### Scatter Plots by Sex and Age
![Scatter Plots](bcd53522-6c1a-4c9a-9af4-ea78d0ff0f40.jpg)

### Age Group Comparisons
![Age Group Comparisons](8f845907-6bb4-4c3d-a3bc-ca24f48c6f9e.jpg)

### Heart Failure Prediction Dashboard
![Heart Failure Prediction](e05517c2-1a30-401f-a7e2-76a58fe193b6.jpg)

### Population Overview
![Population Overview](2c3dfcbc-1f41-45bd-a074-48caa6460e2c.jpg)

### Gender & Age Comparison
![Gender & Age Comparison](7c2ba19a-5cca-4cdb-b586-6767ec71662b.jpg)

### Multivariate Insights
![Multivariate Insights](63db73ef-1591-44f3-9cdb-d5e865eb9aad.jpg)

---

## Dataset

- **Source:** [Heart Failure Prediction Dataset — Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Size:** 918 patients with clinical and demographic records
- **Key variables:** Age, Sex, ChestPainType, Cholesterol, FastingBloodSugar, RestingBP, MaxHR, ExerciseAngina, Oldpeak, ST_Slope, HeartDisease

---

## Key Findings

| Metric | Value |
|--------|-------|
| Total Patients | 918 |
| Heart Disease Patients | 508 (55.34%) |
| Overall Survival Rate | 44.66% |
| Average Age | 53.51 years |
| Male Survival Rate | 36.83% |
| Female Survival Rate | 74.09% |
| Avg Resting Blood Pressure | 132.40 mmHg |
| Avg Cholesterol | 198.80 mg/dl |

**Strongest predictors of heart disease (Pearson correlation):**
- Exercise Angina: r = **+0.49**
- Oldpeak (ST depression): r = **+0.41**
- Maximum Heart Rate: r = **−0.40**
- Age: r = **+0.28**

**Highest-risk demographic:** Males aged 60+ (heart disease rate: 82%)

---

## Research Questions Addressed

1. Data cleaning and preprocessing in Power Query
2. Building a suitable data model with DAX measures
3. Correlation matrix with heatmap
4. Scatter plots with predictive zones
5. Clustered bar charts for age group comparisons
6. KPI cards — survival rate, average age, mortality risk
7. Custom drillthrough reports for survivors vs non-survivors
8. Which factors are strongly associated with heart failure?
9. Are there differences based on gender or age?
10. Which demographic groups are most at risk?
11. Heatmaps, cluster visualisations and KPIs
12. Survival rate differences between genders at various ages
13. Can death probability be predicted using ejection fraction and diabetes?
14. What parameter combinations are most common among survivors?
15. How does high blood pressure affect survival?
16. Which variable has the highest correlation with mortality?

---

## Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query** — data cleaning, type validation, value replacement, categorisation
- **DAX** — custom measures (KPIs, % Heart Disease, survival rates, Pearson correlation via CROSSJOIN)
- **Dataset:** CSV from Kaggle

---

## Files

```
├── ergasia.pbix     # Full Power BI report with all dashboards
└── README.md        # This file
```

> **Note:** The source dataset (`heart.csv`) is not included. Download it from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) and load it into Power BI to refresh the report.

---

## Author

**Stefanos Stefanidis**
MSc Artificial Intelligence & Data Analytics
