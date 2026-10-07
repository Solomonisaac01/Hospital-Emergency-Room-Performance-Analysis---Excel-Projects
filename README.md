# 🏥 Hospital Emergency Room Performance Analysis – Excel Dashboard

## 📊 Project Overview

**Hospital Emergency Room Performance Analysis** is an interactive **Microsoft Excel Data Analytics project** designed to analyze emergency room operations, patient flow, waiting time, satisfaction, admission status, gender distribution, age groups, and department referrals.

The dashboard transforms hospital emergency room data into meaningful business and operational insights using **Excel Pivot Tables, Pivot Charts, Slicers, KPI cards, and data visualization techniques**.

This project is designed as a portfolio project for demonstrating practical **Data Analyst / Business Analyst skills**.

---

## 🎯 Business Problem

Hospital emergency departments need to efficiently manage patient flow, waiting times, admissions, and departmental referrals while maintaining a high level of patient satisfaction.

The objective of this project is to analyze emergency room data and answer questions such as:

- How many patients visited the emergency room?
- What is the average patient waiting time?
- What is the overall patient satisfaction score?
- What percentage of patients were attended on time?
- What is the gender distribution of patients?
- How many patients were admitted versus not admitted?
- Which age groups have the highest number of patients?
- Which departments receive the highest number of patient referrals?
- How does patient activity change by month and year?

---

## 📌 Dashboard KPIs

The dashboard displays the following key performance indicators:

| KPI | Value |
|---|---:|
| **Number of Patients** | 9,216* |
| **Average Wait Time** | 35.26 |
| **Satisfaction Score** | 4.99 |
| **Patients Attended On Time** | 38% |

\*The patient count is derived from the admission-status counts displayed in the dashboard: 4,604 not admitted + 4,612 admitted = **9,216 patients**.

---

## 📈 Dashboard Analysis

### 1. Patients Attended Within Time

The dashboard compares patients who experienced:

- **Delay – 62%**
- **Ontime – 38%**

This KPI helps evaluate emergency room service efficiency and identify potential waiting-time issues.

A high delay percentage may indicate the need for improvements in:

- Staff allocation
- Patient triage
- Registration processes
- Bed availability
- Department coordination

---

### 2. Gender-wise Analysis

The dashboard shows the distribution of patients by gender:

| Gender | Patients | Approx. Share |
|---|---:|---:|
| **Female** | 4,487 | 49% |
| **Male** | 4,729 | 51% |

The distribution is relatively balanced, with male patients representing a slightly larger share.

---

### 3. Admission Status

The dashboard compares admitted and non-admitted patients.

| Admission Status | Patients | % of Patients |
|---|---:|---:|
| **Not Admitted** | 4,604 | 49.96% |
| **Admitted** | 4,612 | 50.04% |

The admission split is almost evenly balanced, with admitted patients representing a slightly higher proportion.

This can help hospitals understand the relationship between emergency visits and inpatient admissions.

---

### 4. Patients by Age Group

The dashboard analyzes patients across different age groups.

| Age Group | Patients |
|---|---:|
| **0–09** | 1,176 |
| **10–19** | 1,160 |
| **20–29** | 1,207 |
| **30–39** | 1,191 |
| **40–49** | 1,137 |
| **50–59** | 1,147 |
| **60–69** | 1,150 |
| **70–79** | 1,048 |

The **20–29 age group** has the highest number of patients among the displayed groups, with **1,207 patients**.

The **70–79 age group** has the lowest count, with **1,048 patients**.

---

### 5. Patients by Department Referral

The dashboard displays patient referrals to different departments.

| Department Referral | Patients |
|---|---:|
| **None** | 5,400 |
| **General Practice** | 1,840 |
| **Orthopedics** | 995 |
| **Physiotherapy** | 276 |
| **Cardiology** | 248 |
| **Neurology** | 193 |
| **Gastroenterology** | 178 |
| **Renal** | 86 |

A large number of patients have **no department referral**, while **General Practice** and **Orthopedics** are the highest referral categories among the displayed departments.

This analysis can help with departmental workload planning and resource allocation.

---

## 🎛️ Interactive Filters

The dashboard includes interactive Excel slicers for:

### Year

Users can filter the dashboard by:

- 2023
- 2024

### Month

The dashboard provides monthly filtering options:

- January
- February
- March
- April
- May
- June
- July
- August
- September
- October
- November
- December

These filters allow users to analyze emergency room performance for a specific year or month.

---

## 🔍 Key Insights

Based on the dashboard:

- The dashboard represents **9,216 emergency room patients** based on the displayed admission-status counts.
- **62% of patients experienced a delay**, while **38% were attended on time**.
- The average waiting time shown is **35.26**.
- The satisfaction score is **4.99**, indicating a high reported satisfaction level in the displayed dashboard.
- The gender distribution is nearly balanced, with **51% male and 49% female** patients.
- Admission status is almost evenly split: **50.04% admitted** versus **49.96% not admitted**.
- Patients aged **20–29** form the largest displayed age group.
- Patients aged **70–79** form the smallest displayed age group.
- **General Practice** is the largest department referral after patients with no referral.
- **Orthopedics** is the second-largest named department referral.
- The high delay percentage highlights an opportunity to improve emergency room response and patient flow.

---

## 💡 Business Recommendations

Based on the dashboard analysis, hospitals can:

1. **Reduce patient waiting times** by identifying the main causes of delays.
2. **Optimize staffing levels** during high-volume periods.
3. **Improve triage and registration processes** to speed up patient assessment.
4. **Monitor department referrals** to ensure adequate resources are available.
5. **Track admission patterns** to improve bed and inpatient capacity planning.
6. **Analyze age-group demand** to support appropriate medical resource allocation.
7. **Monitor patient satisfaction** alongside waiting time to understand service quality.
8. **Compare monthly and yearly performance** to identify operational trends.
9. **Investigate the 62% delay rate** and establish measurable targets for improving on-time patient service.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- Excel Pivot Tables
- Pivot Charts
- Excel Slicers
- KPI Cards
- Data Cleaning
- Data Aggregation
- Data Visualization
- Dashboard Development
- Business Analysis

---

## 🧹 Data Analysis Workflow

### Step 1 – Data Collection

The hospital emergency room dataset contains information related to:

- Patients
- Dates
- Patient demographics
- Admission status
- Waiting time
- Satisfaction score
- Department referrals
- Patient attendance status

### Step 2 – Data Cleaning

The dataset was prepared by checking for:

- Missing values
- Duplicate records
- Incorrect data types
- Date formatting
- Inconsistent categorical values
- Numerical formatting

### Step 3 – Data Preparation

Analytical fields were prepared for:

- Year
- Month
- Gender
- Age Group
- Admission Status
- Department Referral
- Wait Time
- Satisfaction Score
- Attendance Status

### Step 4 – Data Analysis

Pivot Tables and calculations were used to analyze:

- Total Patients
- Average Wait Time
- Satisfaction Score
- On-time vs Delayed Patients
- Gender Distribution
- Admission Status
- Patients by Age Group
- Department Referrals
- Year-wise performance
- Month-wise performance

### Step 5 – Dashboard Development

The final Excel dashboard was designed using:

- KPI cards
- Doughnut charts
- Bar charts
- Column charts
- Data tables
- Slicers
- Interactive filters

---

## 📊 Dashboard Preview

![Hospital Emergency Room Dashboard](Main%20%28Screen_shot%29%281%29.png)

---

## 📂 Project Structure

```text
Hospital-Emergency-Room-Performance-Analysis/
│
├── Hospital_Emergency_Room_Analysis.xlsx
├── Main (Screen_shot)(1).png
└── README.md
```

---

## 🚀 How to Use

1. Download the Excel workbook from this repository.
2. Open the workbook using **Microsoft Excel**.
3. Navigate to the dashboard sheet.
4. Use the **Year** slicer to select 2023 or 2024.
5. Use the **Month** slicer to analyze individual months.
6. Review the KPI cards and charts.
7. Compare patient flow, waiting time, admissions, referrals, and demographics.
8. Use the insights to support operational decision-making.

---

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

- **Excel Data Analysis**
- **Data Cleaning**
- **Pivot Tables**
- **Pivot Charts**
- **Interactive Dashboard Development**
- **KPI Creation**
- **Data Visualization**
- **Healthcare Data Analysis**
- **Patient Flow Analysis**
- **Operational Performance Analysis**
- **Demographic Analysis**
- **Trend Analysis**
- **Business Intelligence**
- **Data Storytelling**
- **Business Recommendations**

---

## 📌 Project Outcome

The project transforms emergency room data into an interactive Excel dashboard that provides a clear view of **patient volume, waiting time, service delays, satisfaction, admissions, gender distribution, age-group demand, and department referrals**.

The dashboard demonstrates how Excel can be used to convert raw healthcare data into actionable insights for **operational planning, resource allocation, patient-flow improvement, and data-driven decision-making**.

---

## 👨‍💻 Author

**Solomon Isaac**

Aspiring Data Analyst | Excel | SQL | Python | Power BI

---

⭐ If you find this project useful, consider giving the repository a **star** on GitHub.
