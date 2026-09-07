# HR Analytics Dashboard (Power BI)

An interactive Human Resources analytics dashboard developed with **Power BI Desktop** to monitor workforce turnover, evaluate retention drivers, and discover patterns across employee demographics, roles, and compensation.

---

## Dashboard Preview
![HR Analytics Dashboard](HR%20ANALYTICS%20screenshot.png)

---

## Project Overview
Employee turnover creates significant operational disruption and replacement costs. This project cleanses, models, and visualizes 1,480 employee records from `HR_Analytics.csv` to identify at-risk cohorts and assist HR leadership in data-backed decision-making.

### Key Metrics
* **Total Employees:** 1,480
* **Attrition Count:** 238
* **Attrition Rate:** 16.1%
* **Average Age:** 36.9 years
* **Average Monthly Income:** $6,505
* **Average Tenure:** 7.0 years

---

## Technical Workflow & Features
* **Data Cleaning & Power Query:**
  * Cleaned missing manager tenure data and validated data types.
  * Created categorical groupings for continuous columns (`AgeGroup`, `SalarySlab`).
* **DAX Measures:**
  * Total Headcount, Leavers, Attrition Rate %, Average Monthly Income, and Average Tenure.
* **Interactive Visualizations:**
  * **KPI Scorecards:** High-level executive overview of workforce metrics.
  * **Attrition by Department & Role:** Breakdown identifying high turnover roles (Laboratory Technicians, Sales Executives).
  * **Attrition by Age & Tenure:** Identifies elevated risk within early-career staff (ages 26–35).
  * **Salary Slab Analysis:** Highlights turnover concentration in lower compensation bands ("Upto 5k").
  * **Cross-Filtering & Slicers:** Dynamic drill-downs by department, gender, and education field.

---

## Key Insights
* **High-Risk Age Bracket:** Employees aged 26–35 represent nearly **49%** of total exits.
* **Role Vulnerability:** Laboratory Technicians (62 leavers) and Sales Executives (58 leavers) observe the highest attrition volumes.
* **Salary Correlation:** Employees in the lowest salary bracket ("Upto 5k") show the highest exit rates compared to higher compensation tiers.

---

## Repository Files
* `power Bi HR Analytics Dashboard.pbix`: Full Power BI report file with model and visuals.
* `HR_Analytics.csv`: Raw HR dataset.
* `HR ANALYTICS screenshot.png`: Visual preview of the dashboard.
*
