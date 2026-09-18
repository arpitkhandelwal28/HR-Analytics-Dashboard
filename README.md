# HR Analytics Dashboard 📊

An interactive **HR Analytics Dashboard** built with **Microsoft Power BI** to analyze employee attrition, workforce demographics, job roles, overtime, business travel, income, and tenure.

The dashboard is designed to help HR teams quickly understand **who is leaving, where attrition is concentrated, and which employee factors are associated with higher attrition rates**.

![HR Analytics Dashboard](image/Screenshot%202026-09-18%20144023.png)

## 🎯 Project Objective

The objective of this project is to transform employee-level HR data into an interactive dashboard that provides actionable insights into:

- Overall employee headcount and attrition
- Attrition rate across departments and job roles
- Gender and marital-status distribution
- Overtime and business-travel patterns
- Average monthly income and employee tenure
- Workforce segments with comparatively higher attrition rates

## 📌 Key KPIs

| KPI | Value |
|---|---:|
| Total Employees | 1,413 |
| Attrition Count | 229 |
| Attrition Rate | 16.21% |
| Average Age | 37 |
| Average Monthly Income | ₹6,520 |
| Average Years at Company | 7.0 |

> KPI values shown above reflect the dashboard snapshot included in this repository.

## 📊 Dashboard Analysis

### 1. Employee Attrition
A donut chart provides an overview of employees who stayed versus employees who left the organization.

- **229 employees** are shown as attrition.
- The dashboard shows an overall attrition rate of **16.21%**.

### 2. Attrition by Department
The dashboard compares attrition rates across departments to identify departments with relatively higher employee turnover.

### 3. Attrition by Job Role
Job-role analysis highlights differences in attrition across individual positions, helping identify roles that may require deeper HR investigation.

### 4. Employee Demographics
The dashboard includes employee distribution by:

- Gender
- Marital Status
- Department
- Job Role

### 5. Overtime Analysis
Employees are segmented based on overtime status to examine the relationship between overtime and attrition.

### 6. Business Travel Analysis
Business-travel frequency is compared with attrition rate across:

- Travel Frequently
- Travel Rarely
- Non-Travel

## 🔎 Key Insights from the Dashboard

- The dashboard contains **1,413 employees** and **229 recorded attritions**.
- Attrition varies considerably across departments and job roles.
- **Sales Representatives** show a comparatively high attrition rate in the displayed job-role analysis.
- Employees who travel frequently show a higher attrition rate than the other travel categories shown.
- Attrition also differs across marital-status groups.
- Overtime status provides another useful dimension for investigating employee turnover.

These observations are descriptive findings from the dashboard and can be used as starting points for further HR investigation.

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
  - Power Query
  - DAX
  - Interactive visualizations
  - Slicers and filters
- **CSV** for source data
- **GitHub** for project versioning and documentation

## 📁 Repository Structure

```
HR-Analytics-Dashboard/
│
├── HR_Analytics.csv
├── HR_Analytics.pbix
├── image/
│   └── HR_Analytics_Dashboard.png
└── README.md
```

## 🎛️ Dashboard Filters

The dashboard includes interactive filters for:

- Department
- Job Role
- Marital Status
- Gender
- Business Travel
- OverTime

These slicers allow users to drill down into specific employee segments and analyze how workforce characteristics relate to attrition.

## 💡 Business Questions Addressed

This dashboard can be used to answer questions such as:

1. What is the overall employee attrition rate?
2. Which departments have higher attrition rates?
3. Which job roles have higher employee turnover?
4. How does attrition vary by marital status?
5. Is attrition different for employees working overtime?
6. How does business-travel frequency relate to attrition?
7. What is the current workforce size and average tenure?
8. What employee segments should HR investigate further?

## 🚀 How to Use

1. Download or clone this repository.
2. Open `HR_Analytics.pbix` using **Power BI Desktop**.
3. If required, update the CSV data source path.
4. Refresh the dataset.
5. Use the slicers to explore different employee segments.
6. Review the KPI cards and charts to investigate attrition patterns.

## 📷 Dashboard Preview

The dashboard screenshot is available in:

`image/Screenshot%202026-09-18%20144023.png`

## 👨‍💻 Author

**Arpit Khandelwal**

B.Tech – Computer Science  
Aspiring Data Analyst | Power BI | SQL | Excel | Python

---

⭐ If you find this project useful, feel free to explore the repository and connect with me on GitHub.
