# 📊 HR Attrition Dashboard — Power BI

An interactive Power BI report that analyzes employee attrition across **5,000 employees**. It shows who leaves, when they leave, and which factors (tenure, salary, department, job role, demographics) are linked to higher attrition.

![Overview](images/overview.png)

---

## 🎯 Project Goal

Help HR teams answer key questions:
- How many employees are leaving, and what is the attrition rate?
- Which departments and job roles have the highest attrition?
- Do salary, tenure, or marital status affect the likelihood of leaving?
- How has attrition changed over the years?

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **SQL Server** | Data storage |
| **Power Query** | Data cleaning and transformation |
| **DAX** | KPI measures (attrition rate, averages, counts) |
| **Power BI Desktop / Service** | Data modeling, visualization, and publishing |

---

## 📌 Key Metrics (KPIs)

| Metric | Value |
|--------|-------|
| Total Employees | **5,000** |
| Active Employees | **4,263** |
| Employees Who Left | **737** |
| Attrition Rate | **14.74%** |
| Average Salary | **$5,279** |
| Average Tenure | **6.31 years** |

---

## 🗂️ Report Pages

The report has **6 pages** with a side navigation menu, plus **Year**, **Department**, and **Job Role** filters on every page. A *Clear all filters* button resets the view.

### 1. Overview
Attrition trend over time, attrition by gender, age group, department, top 5 job roles, and marital status.
![Overview](images/overview.png)

### 2. Attrition Analysis
Attrition rate by tenure, salary band, marital status, and business travel.
![Attrition Analysis](images/attrition-analysis.png)

### 3. Demographics
Employee breakdown by age and gender, education and gender, marital status, and city.
![Demographics](images/demographics.png)

### 4. Performance
Performance rating distribution, average rating by department, and ratings by job role.
![Performance](images/performance.png)

### 5. Compensation
Average bonus by department, salary band distribution, and average salary by department.
![Compensation](images/compensation.png)

### 6. Workforce
Employment status (active vs. terminated), remote work share, and headcount trend over time.
![Workforce](images/workforce.png)

---

## 💡 Key Insights

- **Newer employees leave more often.** Employees with 0–3 years at the company have the highest attrition rate (15.68%), compared to 14.20% for those with 9+ years.
- **Higher pay is linked to lower attrition.** The $7,000–$8,999 salary band has the lowest attrition rate (12.90%). The $3,000–$4,999 band has the highest (15.98%).
- **Operations has the highest attrition** by department (16.95%), while **IT has the lowest** (12.78%).
- **Coordinator** is the job role with the highest attrition rate (16.95%).
- **Attrition peaked in 2021** (80 employees) and has been declining since, down to 50 in 2026.
- **Salary, bonus, and performance are very similar across departments.** Differences in attrition are therefore likely driven by other factors, such as role type or workload.
- The workforce is evenly spread across **Chicago, Dallas, and New York**, and about **half of employees work remotely**.

---

## 📁 Repository Structure

```
HR-Attrition-Dashboard/
├── HR_Attrition_Dashboard.pbix   # Power BI report file
├── images/                       # Dashboard screenshots
│   ├── overview.png
│   ├── attrition-analysis.png
│   ├── demographics.png
│   ├── performance.png
│   ├── compensation.png
│   └── workforce.png
└── README.md
```

---

## ▶️ How to Use

1. Download or clone this repository.
2. Open `HR_Attrition_Dashboard.pbix` in **Power BI Desktop**.
3. Use the side menu to switch pages, and the filters at the top to explore by year, department, or job role.

---

## 👩‍💻 Author

**Nigar Shahmuradova** — Data Analyst | Microsoft Certified: Power BI Data Analyst Associate (PL-300)

🔗 [LinkedIn](https://www.linkedin.com/in/your-profile) · [Power BI Live Report](https://app.powerbi.com/your-link)
