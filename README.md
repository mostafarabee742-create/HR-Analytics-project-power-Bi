# 📊 HR Analytics Dashboard - Power BI Project

## 🎯 Project Overview

A comprehensive HR Analytics solution built in Power BI to provide actionable insights into workforce dynamics, employee attrition, and satisfaction metrics. This multi-page interactive dashboard empowers HR leadership and stakeholders to make data-driven decisions on talent management and retention strategies.

## 🔍 Business Problem

Organizations struggle to understand the factors driving employee turnover and satisfaction. This dashboard addresses critical questions:
- What is our current workforce composition and attrition rate?
- Which departments, age groups, or locations experience highest turnover?
- How do travel frequency and tenure impact attrition?
- What drives employee satisfaction across different demographics?

## 📈 Key Features

### Page 1: Employee Overview
- **Total Workforce Metrics**: Real-time view of total, active, and inactive employees (1,470 total | 1,233 active | 237 inactive)
- **Demographic Analysis**: 
  - Age group distribution (20-30: 874 employees showing highest representation)
  - Gender breakdown (Female: 45.9% | Male: 44.29% | Non-Binary & Prefer Not to Say: 9.81%)
- **Geographic Insights**: State-level attrition rates with dual-axis visualization
- **Growth Trends**: Cumulative active employee growth from 2012 to 2022
- **Overtime Analysis**: Split between overtime (Yes: 944 | No: 289)

### Page 2: Attrition Analysis
- **Overall Attrition Rate**: 16.12% with year-over-year trend analysis
- **Tenure Analysis**: Attrition rate by years at company (highest at 31.58% for new hires)
- **Geographic Patterns**: Multi-line comparison across CA, IL, and NY
- **Travel Impact**: Clear correlation between travel frequency and attrition
  - Some Travel: 14.96% attrition
  - Frequent Traveler: 8.00% attrition
  - No Travel: 5.00% attrition
- **Demographic Breakdown**: 
  - Age group attrition patterns
  - Overtime impact (75% no overtime vs 25% overtime)
- **Compensation Analysis**: Average salary by job role vs attrition rate correlation


### Page 3: Satisfaction Analysis
- **Multi-Dimensional Satisfaction Scores** (Scale 1-5):
  - Environment: 3.87
  - Job: 3.43
  - Relationships: 3.43
  - Work-Life Balance: 3.41
- **Trend Analysis**: 10-year satisfaction trends across all dimensions
- **Travel Segmentation**: Satisfaction levels by travel frequency (1,043 employees with some travel)
- **Demographic Deep-Dive**: Satisfaction metrics by age group and ethnicity
- **Year-over-Year Trends**: Total satisfaction average from 2010-2020


## 🛠️ Technical Implementation

### Data Modeling
- Star schema design for optimal performance
- Calculated measures using DAX for KPIs and metrics
- Dynamic filtering across all visualizations
- Year and department slicers for interactive analysis


### Visualizations Used
- Gauge charts for KPIs
- Donut charts for categorical breakdowns
- Combo charts for dual-axis analysis
- Line charts for trend analysis
- Bar charts for group comparisons
- Interactive slicers and filters

## 💡 Key Insights

1. **Critical Retention Window**: Attrition peaks at 31.58% for employees in their first year, declining to 0.7% after 10 years
2. **Travel Paradox**: Frequent travelers have lower attrition (8%) compared to some travel (14.96%)
3. **Steady Growth**: Active employee base grew 870% from 2012 (127) to 2022 (1,233)
4. **Overtime Burden**: 76.5% of workforce works overtime, potential burnout risk
5. **Satisfaction Stability**: Satisfaction scores remain consistent (3.4-3.9) across all dimensions with slight improvement post-2015

## 🎓 Skills Demonstrated

- **Data Modeling**: Relationships, star schema design, data normalization
- **DAX**: Advanced calculations, time intelligence, statistical measures
- **Data Visualization**: Chart selection, color theory, UX/UI best practices
- **Business Intelligence**: KPI design, stakeholder communication, actionable insights
- **Power BI**: Interactive dashboards, slicers, cross-filtering, formatting

## 📊 Tools & Technologies

- **Power BI Desktop**: Dashboard development and data modeling
- **DAX**: Calculated measures and columns
- **Power Query**: Data transformation and cleaning
- **Excel/CSV**: Source data format

## 🚀 Impact & Applications

This dashboard enables HR teams to:
- Identify at-risk employee segments for targeted retention programs
- Optimize recruitment strategies based on historical growth patterns
- Benchmark satisfaction scores and track improvement initiatives
- Allocate resources to departments with highest attrition
- Design compensation packages aligned with market and retention goals

## 📁 Project Structure

```
hr-analytics-dashboard/
│
├── Data/
│   ├── Employee_Data.xlsx
│   ├── Attrition_Data.xlsx
│   └── Satisfaction_Data.xlsx
│
├── Reports/
│   └── HR_Analytics_Dashboard.pbix
│
├── employee_overview.png
├── attrition_analysis.png
├── satisfaction_analysis.png
│
└── README.md
```

## 🔗 Connect With Me

I'm passionate about transforming data into actionable insights. Let's connect!

- **LinkedIn**: www.linkedin.com/in/mostafa-rabee74
- **GitHub**: https://github.com/mostafarabee742-create


**⭐ If you found this project valuable, please consider starring the repository!**

*Built with ❤️ and Power BI*
