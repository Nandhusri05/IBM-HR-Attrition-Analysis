# IBM HR Analytics - Employee Attrition Analysis

## Project Overview

Employee attrition is one of the most significant challenges organizations face, as high turnover increases recruitment costs, reduces productivity, and impacts overall business performance.

This project performs an end-to-end analysis of the IBM HR Analytics Employee Attrition dataset to identify workforce patterns and factors associated with employee attrition.

The project combines exploratory data analysis (EDA) using Python with an interactive Power BI dashboard to transform raw HR data into meaningful business insights. The analysis focuses on employee demographics, compensation, experience, job characteristics, and workplace factors to support data-driven employee retention strategies.

---

## Business Problem

Employee turnover affects organizational performance, operational efficiency, and workforce stability.

The objective of this project is to analyze employee demographics, job-related characteristics, compensation, and experience to identify trends associated with employee attrition and provide business recommendations that can help improve employee retention.

---

## Dataset Information

- **Dataset:** IBM HR Analytics Employee Attrition & Performance
- **Records:** 1,470 Employees
- **Features:** 35 Employee Attributes

The dataset includes information related to:

- Employee Demographics
- Department
- Job Role
- Monthly Income
- Overtime
- Work-Life Balance
- Job Satisfaction
- Years at Company
- Years with Current Manager
- Stock Option Level
- Performance Rating
- Employee Attrition

---

## Tools & Technologies Used

### Python Analysis

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

### Business Intelligence

- Power BI
- Power Query
- DAX
- Data Visualization
- Interactive Dashboard Design

---

## Project Workflow

1. Business Problem Definition
2. Dataset Overview
3. Data Understanding
4. Data Quality Assessment
5. Data Cleaning
6. Exploratory Data Analysis (EDA)
7. Business Insights
8. Power BI Data Preparation
9. DAX Measure & Calculated Column Creation
10. Interactive Dashboard Development
11. Key Findings
12. Business Recommendations
13. Conclusion

---

## Exploratory Data Analysis

The exploratory analysis investigates workforce characteristics and employee attrition from multiple perspectives.

### Workforce Overview

- Employee Distribution
- Department Distribution
- Gender Distribution
- Marital Status Distribution
- Job Role Distribution

### Employee Attrition Analysis

- Overall Attrition Rate
- Department-wise Attrition
- Job Role-wise Attrition
- Department & Job Role Analysis
- Gender Analysis
- Overtime Analysis
- Marital Status Analysis

### Employee Demographics

- Age Distribution
- Age Group Analysis
- Age Group & Gender Attrition
- Education Analysis

### Compensation Analysis

- Monthly Income Distribution
- Department-wise Income
- Income vs Attrition
- Stock Option Analysis

### Experience Analysis

- Total Working Years
- Years at Company
- Years with Current Manager
- Years Since Last Promotion

### Correlation Analysis

- Correlation Matrix
- Positive & Negative Correlations
- Correlation with Attrition

---

## Power BI Dashboard

An interactive two-page Power BI dashboard was developed to present the key workforce metrics and attrition patterns identified during the analysis.

The dashboard enables users to explore employee attrition from both a high-level workforce perspective and a detailed attrition-driver perspective.

### Page 1 - HR Attrition Overview

The **HR Attrition Overview** page provides a high-level summary of the organization's workforce and major attrition patterns.

#### Key KPIs

- **Total Employees:** 1,470
- **Active Employees:** 1,233
- **Employees Left:** 237
- **Attrition Rate:** 16.12%

#### Visual Analysis

- Employees by Department
- Attrition Rate by Department
- Attrition Rate by Age Group
- Attrition Rate by Overtime
- Attrition Rate by Gender

#### Interactive Filters

- Department
- Job Role

---

### Page 2 - Attrition Drivers & Employee Insights

The **Attrition Drivers & Employee Insights** page provides a deeper analysis of workforce factors associated with employee attrition.

#### Visual Analysis

- Attrition Rate by Job Role
- Attrition Rate by Tenure Bands
- Attrition Rate by Income Band
- Attrition Rate by Business Travel
- Attrition Rate by Stock Option Level
- Attrition Rate by Job Satisfaction
- Attrition Rate by Marital Status
- Attrition Rate by Work-Life Balance

#### Interactive Filters

- Department
- Job Role

These filters allow users to dynamically explore attrition patterns across different employee groups and organizational segments.

---

## Key Dashboard Insights

The Power BI dashboard highlights several important workforce patterns:

- The organization has an overall **attrition rate of 16.12%**, with 237 employees leaving out of 1,470 employees.
- **Sales** has the highest department-level attrition rate at approximately **20.6%**.
- Employees aged **18–25** have the highest attrition rate among the analyzed age groups.
- Employees working **overtime** have substantially higher attrition than employees who do not work overtime.
- **Sales Representatives** show the highest attrition rate among job roles.
- Employees with **0–5 years of tenure** have higher attrition compared with most longer-tenure groups.
- Employees in the lowest analyzed **income band** show comparatively high attrition.
- Employees who **travel frequently** show higher attrition than employees who travel rarely or do not travel.
- Employees with **no stock options** have the highest attrition among stock option levels.
- Employees reporting **low job satisfaction** show comparatively higher attrition.
- **Single employees** show higher attrition than married and divorced employees.
- Employees with the lowest **work-life balance** rating show substantially higher attrition.

---

## Key Findings

- Employee attrition varies significantly across departments, job roles, and employee demographics.
- Sales Representatives experience the highest attrition among all job roles.
- Employees working overtime exhibit substantially higher attrition rates.
- Younger employees and employees with shorter organizational tenure are more likely to leave the company.
- Single employees show higher attrition compared to married and divorced employees.
- Employees with lower monthly income and no stock options experience comparatively higher attrition.
- Frequent business travelers experience comparatively higher attrition.
- Lower job satisfaction and poorer work-life balance are associated with higher employee attrition.
- Strong positive correlations exist between experience, job level, and monthly income.
- Employee attrition is influenced by multiple factors rather than any single variable.

---

## Business Recommendations

Based on the analysis, the following actions could help organizations improve employee retention:

- **Review overtime policies** to reduce excessive workloads and improve employee work-life balance.
- **Strengthen onboarding and early-career retention programs**, particularly for employees within their first few years at the organization.
- **Evaluate compensation and stock option policies** for lower-income employees and employees without stock benefits.
- **Provide clear career growth and learning opportunities** to improve long-term employee engagement.
- **Implement department and job-role-specific retention strategies**, particularly for Sales and Sales Representatives.
- **Review frequent business travel requirements** and explore flexible alternatives where possible.
- **Monitor employee job satisfaction and work-life balance** through regular feedback and engagement initiatives.
- **Enhance leadership support** through regular employee communication, recognition, and career discussions.
- **Use a data-driven HR monitoring approach** to continuously track attrition trends and identify emerging workforce risks.

---

## Project Outcome

This project demonstrates how Python-based exploratory data analysis and Power BI can be combined to analyze workforce data and uncover meaningful employee attrition patterns.

Python was used for data understanding, cleaning, exploratory analysis, statistical interpretation, and identifying important workforce trends. Power BI was then used to transform these findings into an interactive two-page dashboard that enables users to explore key HR metrics and attrition drivers.

The project demonstrates an end-to-end data analytics workflow—from raw data exploration and analysis to business intelligence reporting, data storytelling, and actionable recommendations.

---

## Repository Structure

```text
IBM-HR-Analytics-Employee-Attrition-Analysis/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── notebooks/
│   └── IBM_HR_Analytics_EDA.ipynb
│
├── dashboard/
│   └── IBM_HR_Attrition_Dashboard.pbix
│
├── images/
│   ├── HR_Attrition_Overview.png
│   └── Attrition_Drivers.png
│
└── README.md
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Analytics
- Statistical Interpretation
- Correlation Analysis
- HR Analytics
- Python Programming
- Pandas
- Matplotlib
- Seaborn
- Power BI
- Power Query
- DAX
- KPI Development
- Dashboard Development
- Interactive Data Visualization
- Business Recommendation Writing
- Data Storytelling

---

## Future Improvements

- Develop predictive machine learning models for employee attrition.
- Perform feature importance analysis to identify the strongest predictors of employee turnover.
- Compare multiple classification algorithms for attrition prediction.
- Extend the Power BI dashboard with predictive attrition insights.

---

## Author

**Nandhusri Rajaraman**

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization | Business Analytics
