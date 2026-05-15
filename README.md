# 📊 Data Jobs Dashboard — Power BI

An interactive Power BI dashboard analyzing **478K+ real-world data job postings**, uncovering salary trends, hiring patterns, job types, and role-specific insights across the data industry.

---

## 🖼️ Dashboard Preview

### Page 1 — Main Overview
![Data Jobs Dashboard](screenshots/page1.png)

### Page 2 — Job Title Drill Through
![Job Title Drill Through](screenshots/page2.png)

> 📌 *Save your screenshots in a `screenshots/` folder inside the repo as `page1.png` and `page2.png`.*

---

## 📌 Overview

This dashboard is built on a dataset of **~479K data job postings** and gives a complete picture of the data job market — from salary benchmarks to hiring platform breakdowns. It features **2 interactive report pages** with drill-through functionality.

---

## 📊 Dashboard Pages & Visuals

### Page 1 — Data Jobs Dashboard

| Visual | Description |
|---|---|
| **KPI Cards** | Total Job Count (478.9K), Salary Star Rating (★★★★☆), Median Yearly Salary ($113K), Median Hourly Salary ($48) |
| **Line Chart** | Job posting trends across Jan–Nov 2024 |
| **Bar Chart** | Highest paying data jobs by median yearly salary |
| **Scatter Plot** | Hourly vs Yearly salary comparison across roles |
| **Matrix Table** | Job title breakdown — count, hourly salary, yearly salary, and trend sparklines |
| **Slicer** | Filter all visuals by job title |

### Page 2 — Job Title Drill Through

> Drill through from any job title on Page 1 to see role-specific details.

| Visual | Description |
|---|---|
| **Gauge Charts** | Median yearly & hourly salary with min/max range |
| **Donut Charts** | Degree requirement %, Remote/WFH %, Health insurance offered % |
| **Map Visual** | Countries that don't mention degree in job postings |
| **Bar Chart** | Job postings count by platform (LinkedIn, Indeed, BeBee, etc.) |
| **Bar Chart** | Job type breakdown (Full-time, Part-time, Contract, etc.) |

---

## 🔍 Key Insights

- 📦 **479K+** data job postings analyzed
- 💰 Median yearly salary across all roles: **$113K**
- ⏱️ Median hourly salary: **$48/hr**
- 🏆 **Senior Data Scientist** and **Senior Data Engineer** are the highest paying roles (~$150K+)
- 🏠 Only **15%** of postings mention remote/WFH availability
- 🎓 **47%** of postings don't require a degree
- 🏥 Only **10%** of postings mention health insurance
- 💼 **89%** of data jobs are full-time positions
- 📢 **LinkedIn** is the dominant job posting platform

---

## 🛠️ Built With

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard design & visualization |
| **Power Query (M)** | Data cleaning & transformation |
| **DAX** | Custom measures (medians, KPIs, sparklines) |

---

## 📂 Dataset

- **Source:** Job postings dataset (`job_postings_flat`)
- **Records:** ~479,000 job postings
- **Time Period:** January 2024 – November 2024
- **Key Fields:** Job title, yearly salary, hourly salary, job platform, remote status, degree requirement, health insurance, job type, country

> This dataset contains publicly available sample job posting data with no personally identifiable information.

---

## 🚀 How to Open

1. Download and install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (free)
2. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/data-jobs-powerbi-dashboard.git
   ```
3. Open `Data_Jobs_Dashboard.pbix` in Power BI Desktop
4. Use the **"Select Job"** slicer to filter by role
5. Click any job title row in the matrix → **Drill through** to Page 2 for role-specific details

---

## 📁 Repository Structure

```
data-jobs-powerbi-dashboard/
│
├── Data_Jobs_Dashboard.pbix     # Main Power BI dashboard file
├── README.md                    # Project documentation
└── screenshots/
    ├── page1.png                # Main dashboard screenshot
    └── page2.png                # Drill through page screenshot
```

---

## 🙋 About

Made by **Nisarg Ranade** — CS undergrad at IIITDM Kancheepuram, interested in data analytics and visualization.

- 🔗 [GitHub](https://github.com/YOUR_USERNAME)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
