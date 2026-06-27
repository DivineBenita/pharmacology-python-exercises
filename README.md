# Pharmacology Python Exercises

Python exercises and biomedical data analysis built during my 
computational biomedical research training — working toward 
graduate research in computational pharmacology and drug 
discovery.

**Author:** Divine (Benita) Esabu, PharmD Student  
**Institution:** University of Benin  
**Started:** June 2026

## Purpose

I am a PharmD student building technical skills in Python, 
statistics, and data analysis to pursue graduate research in 
computational pharmacology, with a long-term goal of contributing 
to drug discovery research relevant to African patient populations.

## Progress Log

### Phase 1 — Foundations (May–November 2026)

**Week 1 (June 2026):** Statistics foundations — mean, median, 
mode, variance, standard deviation, normal distribution, 
empirical rule, outliers, skewness, population vs sample, 
correlation.

**Week 2 (June 2026):** Python core — variables, data types, 
lists, dictionaries, conditionals, loops, and functions. 
Implemented the Cockcroft-Gault equation for estimating 
creatinine clearance.

*More to come as the project progresses.*

## Analysis Projects

### 1. Blood Glucose Statistics Analysis (June 2026)

**Dataset:** Pima Indians Diabetes Dataset (768 patients, 
9 variables)

**Methods:** Manual calculation of mean, median, standard deviation, and outlier detection (2-SD rule) using base Python, cross-checked against Pandas' built-in statistical functions. Visualised distribution using Matplotlib with mean and outlier boundary lines marked.

**Key Findings:**
- Mean glucose level: 120.9 mg/dL
- Standard deviation: 32.0 mg/dL
- The distribution is positively skewed, with a long right tail extending toward higher glucose values.
- 36 values fell outside the 2-SD boundary (57.0 to 18.8)
- Several of these outliers are 0 mg/dL readings, which are clinically impossible and almost certainly represent missing data coded as zero rather than genuine measurements 
— a data quality issue worth flagging before any further analysis

**Tools:** Python (base), Pandas, Matplotlib.

**Notebook:** [day19_mini_analysis.ipynb](day19_mini_analysis.ipynb)
![Glucose distribution chart](day19_glucose_outliers.png)


## Progress Log

### Week 1 (10-16 June 2026) — Statistics Foundations

Built a complete statistics reference covering mean, median, mode, range, variance, standard deviation, normal distribution, empirical rule, outliers, skewness, population vs sample, and correlation — each with definitions, formulas, and biomedical examples. 

[statistics_reference.ipynb](statistics_reference.ipynb)

### Week 2 (17-23 June 2026) — Python Core

Worked through Python fundamentals: variables and data types, lists, dictionaries, conditionals, loops, and functions — applying each concept to clinical scenarios from my PharmD training, including implementing the Cockcroft-Gault equation for creatinine clearance.

[day13_functions.ipynb](day13_functions.ipynb)

### Week 3 (24-26 June 2026) — First Real Analysis

Set up GitHub. Learned Pandas and loaded a real clinical dataset (Pima Indians Diabetes Database, 768 patients) for the first time. Built complete charts connecting visual patterns to Week 1 statistics concepts. Read my first scientific paper using a structured three-pass method. Completed a full mini-analysis combining manual statistics, Pandas, and visualisation into one connected project.

[day19_mini_analysis.ipynb](day19_mini_analysis.ipynb)

### What I'm Building Toward

Specialising in computational neuroscience, drug design, and biomedical data science, with a long-term goal of graduate research at institutions like UCL — bridging clinical pharmacology training with computational methods.
