# 📊 Rohan Mhetre — Financial Data Analytics Portfolio

> Finance + Data Analytics | Power BI · Excel · SQL · Python | Equity Research | DCF Valuation

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/rohanmhetre)
[![Email](https://img.shields.io/badge/Email-rohanmhetre2001@gmail.com-red?style=flat&logo=gmail)](mailto:rohanmhetre2001@gmail.com)
![Location](https://img.shields.io/badge/Location-Pune%2C%20Maharashtra-green?style=flat)

---

## 👋 About Me

 Financial Data Analyst with hands-on experience in **Power BI dashboards**, **Excel analytics**, **SQL**, and **Python (EDA)**. I combine financial domain knowledge (DCF modelling, equity research, NISM Series 8) with data analytics tools to deliver end-to-end business intelligence — from raw data to actionable insights.

- 🔭 Currently building: Financial dashboards & equity research models under **Rohan Capital Research**
- 📈 NISM Series 8 Certified | Equity & Derivatives
- 💼 Open to: Financial Data Analyst · Data Analyst · Equity Research Analyst roles (Pune / Remote)

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **BI & Visualization** | Power BI, DAX, Power Query, Excel |
| **Data & Analytics** | SQL, Python (pandas, numpy, matplotlib, seaborn) |
| **Financial Modeling** | DCF, P/E, EV/EBITDA, Ratio Analysis |
| **Other** | Jupyter Notebook, GitHub, MS Office, Google Sheets |

---

## 📁 Projects

### 1. 🏥 Hospital Management System — Relational Database Design & Analytics
## 📌 Project Overview
This project involves the design, implementation, and optimization of a robust, production-grade **Relational Database Management System (RDBMS)** for a healthcare facility using **MySQL**. The database tracks and automates end-to-end hospital workflows—including department operations, patient admissions, doctor assignments, appointment scheduling, pharmacy inventory, and automated patient billing.

Beyond structural design, the project integrates advanced SQL objects like **Stored Procedures**, **Triggers**, and **Database Views** to enforce data integrity, automate workflows, and provide critical analytics insights to hospital administration.

## 🛠️ Technical Stack & Concepts Used
* **Database Engine:** MySQL
* **Database Design:** Entity-Relationship (ER) modeling, Primary & Foreign Key mapping, Data integrity constraints (`CHECK`, `UNIQUE`, `ENUM`, `DEFAULT`).
* **Advanced SQL Objects:** Views, Stored Procedures, Automation Triggers.
* **Analytical Techniques:** Multi-table `JOIN` operations, Window functions/Aggregations, Conditional logic (`CASE WHEN`).

## 📐 Database Schema & Architecture

The system consists of **10 interconnected tables** designed to eliminate redundancy and maintain Referential Integrity:

1. **`departments`**: Tracks operational blocks and contact channels.
2. **`doctors`**: Contains medical staff information, specialization, and salary structures.
3. **`patients`**: Stores comprehensive demographic and emergency contact files.
4. **`appointments`**: Handles physical consult timings, reasons, and status tracking.
5. **`wards`**: Manages room categories (ICU, Private, General, Emergency) and capacities.
6. **`admissions`**: Coordinates inpatient tracking from intake through discharge diagnosis.
7. **`medicines`**: Tracks pharmacy line items, categories, pricing, and stock levels.
8. **`prescriptions`**: Links outpatient consultations to medicine fulfillment.
9. **`bills`**: Centralized financial ledger capturing totals, payments, and payment statuses.
10. **`staff`**: Manages nursing, pharmacy, laboratory, and administrative workforces.

## 🚀 Advanced Automations & Views

### 1. Database Views (Reporting Layer)
* **`v_active_inpatients`**: A real-time executive dashboard displaying currently admitted patients, their designated wards, diagnoses, and exact duration of their stay (`DATEDIFF`).
* **`v_doctor_revenue`**: Aggregates business performance by doctor, mapping admissions handled directly to the revenue generated.

### 2. Stored Procedures (Application Layer Integration)
* **`sp_admit_patient`**: Streamlines the transactional process of checking a patient into a specific ward, assigning a doctor, logging the diagnosis, and returning the new auto-incremented Admission ID.
* **`sp_discharge_patient`**: Automates discharge management by updating patient status and timestamping the exact exit date.

### 3. Database Triggers (Automation & Integrity Layer)
* **`trg_update_payment_status`**: A conditional `BEFORE UPDATE` trigger on the financial ledger. It eliminates human manual entry errors by automatically evaluating `paid_amount` against `total_amount` to re-classify bills dynamically into **'Paid'**, **'Partial'**, or **'Pending'**.

## 📊 Business Intelligence & Reporting Queries

The database is built to answer key operational and financial questions for hospital administrators:

* **Financial Oversight:** Tracks total billed revenue, actual cash collection, and outstanding dues grouped dynamically per clinical department.
* **Inventory Control:** Implements a low-stock alert reporting pipeline highlighting medicines dropping below 100 units.
* **Operational Efficiency:** Aggregates doctor performance by evaluating total scheduled appointments vs. successfully completed consultations.
* **Patient Segmentation:** Isolates Outpatient Department (OPD) traffic by auditing patients who have strictly utilized consultations without requiring inpatient ward admissions.


### 2. 🏙️ Dubai Real Estate Intelligence Dashboard — Power BI
**Tools:**  Excel Power BI · DAX · Power Query · M Code | **50,000 property listings**

Built end-to-end dashboard analysing AED 11.24B in UAE property inventory across neighborhoods, bedrooms, and listing categories
DAX measures for dynamic KPIs (Total Listings, Avg Price, Avg Price/Sqft, Highest Price); Power Query for ETL & data cleaning
Identified High-End tier dominates at 50% of inventory, with Budget and Mid-Range each at 25% — signalling top-end oversupply risk
Key insight: Neighborhood pricing is nearly flat (Urban AED 227K, Rural AED 224K, Suburb AED 223K) — Category and Bedrooms drive price, not Zone — actionable for investor targeting and developer pipeline planning

📁 View Project →https://www.linkedin.com/posts/rohanmhetre_powerbi-dataanalyst-dataanalytics-ugcPost-7452194475990216706-4yrd?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEJfMigBlO16_F1o852di79Mlcul8YHgSdY

### 3. 🛒 Amazon E-Commerce Sales Dashboard — Power BI
**Tools:** Power BI · DAX · Power Query · Excel | **18,000+ order records**

- Built end-to-end dashboard analysing ₹11,579K in Amazon sales across courier status, fulfilment channels, product categories, and shipping cities
- DAX measures for dynamic KPIs; Power Query for ETL & data cleaning
- Identified Bengaluru, Mumbai, Hyderabad as top hubs; T-shirts as highest-volume category
- **Key insight:** 91.13% orders shipped via Amazon Logistics — actionable for inventory & logistics planning

📂 [View Project →](https://bit.ly/4tiNhto)

---

### 4. 🏥 Hospital Emergency Room Analytics — Excel
**Tools:** MS Excel · Pivot Tables · Dynamic Charts · Slicers | **513 patients**

- Interactive Excel dashboard tracking 513 patients across gender, age groups (0–79), admission rates (52.4%), and satisfaction score (4.96/5)
- KPI cards for Patient Count, Avg. Wait Time (36.3 min), Satisfaction Score
- Department referral chart highlighted General Practice (103) and Orthopedics (65) as high-demand areas
- Monthly slicers (Jan–Jun) for time-series analysis; structured as a reusable reporting template

📂 [View Project →](https://bit.ly/3OeJDBT)

---

### 5. 🏠 Global Airbnb Performance Dashboard — Power BI
**Tools:** Power BI · DAX · Data Cleaning · Data Visualization | **2.79M+ listings across 10 cities**

- Built interactive dashboard analysing Airbnb's global performance across 2.79M+ listings, 182K+ hosts, and 10 cities worldwide
- Analysed listing growth trends: 2015 saw highest surge in new listings; 2016–17 slowdown due to regulatory tightening
- Tracked Airbnb's profitability milestone (late 2016) and first full income-generation year (2017); identified COVID-19 impact on 2019 growth
- Delivered market share by city, property type analysis, and cross-location rating comparisons for strategic insights

📂 [View Project →](https://bit.ly/4sOo2z3)

### 6. ☕ Coffee Shop Sales Analysis — Excel
**Tools:** MS Excel · Pivot Tables · Dynamic Charts · Slicers | **149,116 total footfall across 3 locations**

- Built interactive Excel dashboard analysing $6,98,812 in retail sales across 3 NYC store locations (Astoria, Hell's Kitchen, Lower Manhattan) with month and day-of-week slicers
- Identified peak sales hours at 9–10 AM via hourly quantity trend chart; weekday analysis showed Monday & Friday as highest footfall days
- Top product: Barista Espresso ($91,406) followed by Brewed Chai Tea ($77,082) and Gourmet Brewed Coffee ($70,035)
- Coffee category dominates at 39% of sales; size distribution shows Large & Regular orders split equally at 30% each
- KPI cards track Total Sales, Footfall (149K+), Avg Bill/Person ($4.69), and Avg Order/Person (1.44) for quick management review

📂 [View Project →](https://bit.ly/4cppQJ3)

---

## 🎓 Education & Certifications

- **M.Com** — Professional Accounting & Finance | Jain University, Bangalore (2023–2025)
- **B.Com** — Accounting & Finance | Savitribai Phule Pune University (2020–2023)
- NISM Series 8 — Equity & Derivatives
- Financial Modeling Certification — Mentor Me Career, Pune
- Portfolio Management & Investment Banking — 365 Financial Analyst

---

## 📬 Contact

- 📧 rohanmhetre2001@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/rohanmhetre)

---

*Open to Financial Data Analyst, Data Analyst & Equity Research roles in Pune or Remote.*
