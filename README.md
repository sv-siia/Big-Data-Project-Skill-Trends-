# Skill Trends Insight – Big Data Analyst Job Market in Poland

**Authors:**  
Anastasiia Sviridova  
Porimol Chandro  
Łukasz Janisiów

---

This project analyzes job posting trends for Big Data and Data Analyst roles in Poland, with a focus on identifying in-demand skills, seniority levels, and salary expectations. The insights are intended to help LearnTech Solutions design data-driven training programs aligned with market needs.

## Objectives

- Analyze trends in job demand for Big Data Analyst roles in Poland
- Categorize and standardize in-demand skills
- Identify salary trends by skill group and seniority level
- Provide actionable insights for training program development

## Dataset

- Timeframe: October 2021 – September 2023  
- Source: [Just Join IT](https://justjoin.it) via Kaggle  
- Structure: Job descriptions, job titles, required skills, salary ranges, dates

## Tools & Technologies

- **Programming:** Python  
- **Processing:** Pandas, PySpark  
- **Visualization:** Matplotlib, Seaborn  
- **Platforms:** Kaggle, Google Colab  
- **Version Control:** GitHub

## Methodology

- **Data Filtering:** Selected postings with "big data" or "data analyst" in job titles  
- **Duplicate Removal:** Aggregated by job ID to avoid repetition  
- **Date Encoding:** Created “Quarter-YY” labels for time-series analysis  
- **Skill Standardization:** Harmonized naming (e.g., Powerbi → Power BI, Pyspark → Apache Spark)  
- **Skill Categorization:** Grouped skills into 6 categories:  
  `Programming Languages`, `Big Data`, `Analytics Tools`, `Databases`, `Cloud Platforms`, `General Skills`  
- **Visualization:** Plotted skill demand and salary evolution using line charts and pie charts

## Key Insights

- Certain skills (e.g., Python, Apache Spark, Power BI) consistently remain in high demand  
- Average salaries vary significantly by skill and seniority level  
- Notable fluctuations in demand across different skill groups and time periods

## Future Work

- Analyze emerging tools and technologies (e.g., GenAI, MLOps)
- Extend the dataset geographically (beyond Poland) and update to current year
- Build predictive models for future skill and salary forecasting
