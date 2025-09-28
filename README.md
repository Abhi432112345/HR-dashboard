# HR Analytics Dashboard - Power BI

## 📊 Project Overview

A comprehensive HR analytics dashboard built in Power BI that transforms raw employee data into actionable business intelligence. This interactive dashboard enables HR professionals and business leaders to monitor key workforce metrics, identify trends, and make data-driven decisions about talent management, retention, and organizational planning.

![Dashboard Preview](https://github.com/user-attachments/assets/4ada6685-d28b-4e3e-9d66-e0e128888b63)

## 🎯 Business Value

### Problem Statement
HR departments often struggle with fragmented employee data spread across multiple systems, making it challenging to:
- Quickly assess overall workforce health and composition
- Identify departments with high attrition risks
- Monitor diversity and inclusion metrics
- Plan strategic hiring and retention initiatives
- Analyze compensation equity across the organization

### Solution
This dashboard provides a unified view of HR metrics through:
- **Real-time monitoring** of key performance indicators
- **Interactive filtering** for deep-dive analysis
- **Trend visualization** for historical perspective
- **Department-level insights** for targeted interventions


## 📈 Key Metrics Tracked

### Workforce Overview
- **Total Headcount**: Current employee count (311 employees)
- **Attrition Rate**: 33% - highlighting retention opportunities
- **Average Salary**: Compensation benchmarking
- **Average Age**: Workforce demographic insights

### Diversity & Composition
- **Department Distribution**: Production leads with 209 employees
- **Gender Balance**: Male/Female ratio across organization
- **Marital Status**: Workforce lifestyle demographics
- **Age Distribution**: 49.2% in 36-45 age bracket

### Historical Trends
- **Yearly Headcount Growth**: From 83 employees (2010) to 311 current
- **Attrition Patterns**: Peak turnover events (e.g., 11 departures in 2014)
- **Hiring Sources**: Effectiveness of recruitment channels

## 🛠 Technical Implementation

### Data Architecture
```
HRDataset_v14.xlsx → Power Query → Data Model → Power BI Visualizations
```

### Tech Stack
- **Power BI Desktop** - Primary visualization and reporting platform
- **Power Query** - ETL processes for data transformation and cleaning
- **DAX (Data Analysis Expressions)** - Calculated measures and business logic
- **Star Schema** - Optimized data model with fact and dimension tables

### Data Model Features
- **Relationships**: Established between employee, department, and metric tables
- **Measures**: Dynamic calculations for KPIs and ratios
- **Hierarchies**: Drill-down capabilities for detailed analysis

## 📋 Dataset Information

The analysis uses `HRDataset_v14.xlsx` containing comprehensive employee records:

**Core Attributes:**
- Employee ID, Department, Position, Employment Status
- Compensation: Salary, Bonuses, Pay Rate
- Demographics: Age, Gender, Marital Status
- Employment Details: Hire Date, Termination Date, Recruitment Source
- Performance Metrics: Engagement scores, Special Projects Count

## 🎨 Dashboard Features

### Main Views
1. **Executive Summary** - High-level KPIs and trends
2. **Departmental Analysis** - Drill-down by business unit
3. **Demographic Insights** - Diversity and composition metrics
4. **Historical Trends** - Year-over-year comparisons

### Interactive Elements
- **Cross-filtering**: Click any visual to filter entire dashboard
- **Date slicers**: Analyze specific time periods
- **Department selectors**: Focus on specific business units
- **Export capabilities**: Share insights with stakeholders

## 💡 Key Insights Uncovered

### Strategic Findings
1. **Resource Allocation**: Production department comprises 67% of workforce, suggesting potential optimization opportunities
2. **Retention Challenge**: 33% attrition rate indicates need for improved employee engagement strategies
3. **Growth Trajectory**: Steady expansion from 83 to 311 employees demonstrates organizational scaling
4. **Mature Workforce**: Nearly half of employees in 36-45 age group, informing succession planning

### Actionable Recommendations
- Implement targeted retention programs for high-attrition departments
- Develop knowledge transfer initiatives given mature workforce demographics
- Optimize recruitment strategies based on source effectiveness
- Conduct compensation analysis to ensure equity across demographics

## 📁 Project Structure
```
HR-Dashboard/
│
├── HR_Dashboard.pbix          # Main Power BI file
├── HRDataset_v14.xlsx         # Source data
├── Documentation/             # Additional documentation
├── Screenshots/               # Dashboard preview images
└── README.md                  # This file
```

## 🤝 Contributing

This project welcomes contributions and suggestions. Please feel free to:
- Submit bug reports and feature requests
- Suggest additional metrics or visualizations
- Share improvements to the data model
- Translate documentation to other languages

---

**Built with ❤️ for better HR decision-making**

*For questions or support, please open an issue in this repository.*

