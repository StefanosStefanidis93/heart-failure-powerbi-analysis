# Heart Failure Prediction — Power BI Analysis

## Overview

End-to-end Business Intelligence solution built in **Microsoft Power BI** for analysing clinical and demographic factors associated with heart failure. The project covers the full BI pipeline — from data cleaning and modelling to interactive dashboards — answering **16 research questions** on patient survival, risk factors and demographic patterns.

> Developed as part of the **Business Intelligence Tools II** course, MSc in Artificial Intelligence & Data Analytics.

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

## Dashboards

The report includes a **Home Page Navigation** menu linking to 9 interactive dashboards:

| Dashboard | Description |
|-----------|-------------|
| **KPI Overview** | Survival rate, avg age, mortality risk, segment breakdowns by sex |
| **Correlation Matrix (Heatmap)** | Pearson correlation between all clinical variables via DAX CROSSJOIN |
| **Scatter Plots with Predictive Zones** | Age vs MaxHR, Cholesterol, RestingBP, Oldpeak — split by sex with trend lines |
| **Age Group Comparisons** | Clustered bar charts comparing heart disease prevalence across age groups |
| **Heart Failure Prediction** | Main drillthrough dashboard — survivors vs non-survivors with full KPIs |
| **Population Overview** | Demographic breakdown: sex, age group, blood pressure bucket, Exercise Angina |
| **Gender & Age Comparison** | Survival and disease rates across all age-sex combinations |
| **Multivariate Insights** | Combined heatmap, clustering and KPI view for multivariate analysis |
| **Hospital Dashboard** | Operational-level patient metrics |

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
