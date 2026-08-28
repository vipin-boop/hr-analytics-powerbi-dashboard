# 👥 HR Employee Attrition & Workforce Analytics Dashboard

An interactive **Power BI HR analytics solution** designed to analyze employee attrition, workforce composition, compensation, tenure, employee demographics, and department-level trends.

The dashboard transforms employee-level HR data into actionable insights through an interactive multi-page reporting experience, helping HR teams understand **who is leaving, where attrition is concentrated, how the workforce is distributed, and how salary and tenure vary across the organization.**

---

## 📌 Dashboard Highlights

### 🏠 Workforce Snapshot

The Home page provides a quick executive view of the organization's workforce through key HR indicators:

* **Total Employees**
* **Active Employees**
* **Employees Left**
* **Average Tenure**
* **Average Salary**
* Employee growth over time
* Department-wise workforce distribution
* Gender distribution
* Age-group distribution
* Education-level distribution

Interactive filters allow users to explore these metrics by **Date, Education, Job Title, Payment Method, and Region**.

---

### 📉 Attrition Analysis

The Attrition page focuses specifically on employee turnover and the factors surrounding it.

Key analysis includes:

* **Employees Left**
* **Attrition Rate**
* **Average Tenure of Employees Who Left**
* **Average Job Satisfaction**
* **Average Performance Rating**
* Attrition trends over time
* Attrition by department
* Attrition by job title
* Attrition by performance rating

This page makes it easier to identify departments and employee groups where turnover may require further investigation.

---

### 🌍 Workforce Analysis

The Workforce page provides a broader view of employee distribution and compensation.

It explores:

* Workforce distribution across regions
* Employee tenure distribution
* Workforce by job role
* Workforce and compensation patterns
* Department-level workforce comparisons

The combination of workforce and compensation analysis provides a more complete picture of how employees are distributed throughout the organization.

---

### 👤 Employee Directory

The Employees page provides a detailed **employee-level directory**.

Users can filter and explore individual employee records using:

* Department
* Job Title
* Education
* Region
* Payment Method
* Date

The employee directory also supports **drill-through analysis**, allowing users to move from an employee record into a more focused employee-level view.

---

## 🧩 Data Model

The report uses a structured **fact-and-dimension data model** to organize employee analytics.

### Fact Table

**`Fact_Employee_Attrition`**

Stores the central employee attrition and workforce-related analytical data.

### Dimension Tables

* **`Dim_Employee`** — Employee information
* **`Dim_Department`** — Department details
* **`Dim_Job_Title`** — Job role information
* **`Dim_Education`** — Education categories
* **`Dim_Region`** — Regional information
* **`Dim_Payment_Method`** — Payment method categories
* **`Dim_Date`** — Date-based analysis

This structure separates descriptive attributes from analytical data and supports consistent filtering across dashboard pages.

---

## 📊 Key HR Metrics

The dashboard tracks several core workforce indicators:

| Metric                 | Purpose                                       |
| ---------------------- | --------------------------------------------- |
| **Total Employees**    | Measures overall workforce size               |
| **Active Employees**   | Tracks employees currently retained           |
| **Employees Left**     | Measures employee exits                       |
| **Attrition Rate**     | Measures the proportion of employees who left |
| **Average Salary**     | Evaluates workforce compensation              |
| **Average Tenure**     | Measures employee experience                  |
| **Job Satisfaction**   | Evaluates employee satisfaction               |
| **Performance Rating** | Provides workforce performance context        |

---

## 🛠️ Tools & Technologies

* **Power BI Desktop** — Dashboard development and visualization
* **Power Query** — Data transformation and preparation
* **DAX** — Measures and analytical calculations
* **Microsoft Excel** — Source data preparation
* **Data Modeling** — Fact and dimension architecture
* **Git & GitHub** — Project version control

---

## 📐 Power BI Features Used

The dashboard demonstrates several Power BI capabilities:

* Interactive slicers
* KPI cards
* Cross-filtering
* Drill-through navigation
* Page navigation
* Time-series analysis
* Bar and column charts
* Donut charts
* Treemap visualization
* Geographic mapping
* Employee-level tabular analysis
* Dynamic filtering across dimensions

---

## 🧮 Analytical Approach

The project follows a complete analytics workflow:

**Raw HR Data**
↓
**Data Cleaning & Preparation**
↓
**Data Modeling**
↓
**Dimension & Fact Relationships**
↓
**DAX Measures**
↓
**Interactive Visualizations**
↓
**HR Insights & Analysis**

---

## 💡 Business Value

This dashboard can support HR teams in:

* Monitoring workforce size and composition
* Detecting departments with higher employee turnover
* Understanding attrition patterns across job roles
* Comparing compensation across workforce groups
* Evaluating employee tenure
* Examining relationships between satisfaction, performance, and attrition
* Investigating individual employee records
* Supporting data-driven workforce planning

---

## 📁 Project Structure

```text
HR-Employee-Attrition-Analysis/
│
├── Dataset/
│   └── HR_Data.xlsx
│
├── PowerBI/
│   └── HR_Data_Dashboard.pbix
│
├── Screenshots/
│   ├── Home.png
│   ├── Attrition.png
│   ├── Workforce.png
│   └── Employees.png
│
└── README.md
```

---

## 🚀 Future Enhancements

Potential extensions for the dashboard include:

* Employee attrition prediction
* Advanced HR segmentation
* Salary benchmarking
* Workforce forecasting
* Automated data refresh
* Additional employee satisfaction analysis
* Advanced DAX-driven HR KPIs
* Predictive analytics using machine learning

---

## 🎓 Project Focus

This project demonstrates an end-to-end **Business Intelligence and Data Analytics workflow**, covering:

**Data Preparation → Data Modeling → DAX → Visualization → Interactive Reporting → Business Analysis**

The final dashboard provides a single analytical environment for exploring **workforce structure, employee compensation, tenure, and attrition** at both organizational and individual levels.
