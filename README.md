
# 🏥 Hospital Data Management & Analysis System

This project presents a comprehensive hospital database and visualization solution that simulates real-world healthcare operations using synthetic data. It supports hospital administration in tracking appointments, billing, doctor availability, prescriptions, and room utilization via an interactive **Power BI dashboard** connected to a **relational MS SQL Server database**.

---

## 📌 Project Overview

- **Goal**: To design a normalized hospital database and provide operational and strategic insights using SQL and Power BI.
- **Scope**: Includes ER modeling, data generation, DDL/DML scripting, analytical SQL queries, and real-time dashboard development.
- **Use Case**: Supports hospital executives, finance departments, administrators, doctors, pharmacists, and ward managers in making data-informed decisions.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **MS SQL Server** | Database design and query execution |
| **Power BI** | Visualization and analytics |
| **Python + Faker (via GPT-4)** | Synthetic data generation |
| **Mermaid.js** | ER diagram modeling |

---

## 🧱 Key Components

1. **Entity-Relationship Diagram**  
   - Defined 11 core tables (Patients, Doctors, Appointments, Prescriptions, Rooms, etc.)
   - Enforced referential integrity through PK–FK relationships
2. **Synthetic Data Generation**  
   - 20+ rules used with GPT-4 for generating consistent, realistic healthcare data
3. **SQL Implementation**  
   - DDL scripts for schema creation
   - DML scripts for data insertion
   - Views and queries for business intelligence use cases
4. **Power BI Dashboard**  
   - Connected to SQL Server using views
   - Used DAX for KPIs and calculated measures
   - Designed dashboards per stakeholder needs

---

## 📊 Dashboard Features

| Dashboard | Target User | Key Insights |
|----------|--------------|---------------|
| **Patient & Appointment Overview** | Hospital Admins | Appointment volume, cancellation trends |
| **Doctor Workload Tracker** | Medical Directors | Availability, overbooking, patient load |
| **Billing & Financials** | Finance Teams | Revenue, outstanding balances, department earnings |
| **Room Utilization** | Facility Managers | Occupancy trends, room type usage, turnaround time |
| **Prescription Overview** | Pharmacy | Top medicines, stock levels, prescribing patterns |
| **Executive Summary** | Leadership | High-level KPIs and departmental performance |

---

## 🔍 Sample Business Questions Answered

- Which doctors are consistently overbooked?
- What is the average billing per patient by department?
- Which medicines are prescribed most often?
- What is the room occupancy rate in the past month?
- What percentage of revenue remains unpaid?

---

## 🔒 Access Control

- Admin user with full permissions
- Role-based read-only access for stakeholders
- Views created to ensure secure and performance-optimized Power BI imports

---

## 🚧 Challenges

- Maintaining referential integrity across 11+ interrelated tables
- Generating clean synthetic data while meeting medical realism
- Adjusting Power BI model relationships manually to avoid conflicts
- Building SQL queries to pre-aggregate data for performance in Power BI

---

## ✅ Learning Outcomes

- Mastered **ERD design and SQL constraints** for relational modeling
- Learned **prompt engineering** with GPT-4 to control data output
- Developed **Power BI dashboards** with dynamic KPIs and filters
- Strengthened **problem-solving** and **collaborative development**

---

## 📁 Repository Structure

\`\`\`
├── README.md
├── ERD Diagram
├── SQL Scripts
│   ├── DDL_Tables.sql
│   ├── DML_DataInsertion.sql
│   ├── Views.sql
│   └── Queries_BusinessQuestions.sql
├── PowerBI
│   └── Hospital_Dashboard.pbix
├── Docs
│   ├── Technical_Report.pdf
│   └── Final_Presentation.pdf
\`\`\`

---

## 📚 References

- [Our World in Data – Healthcare Systems](https://ourworldindata.org)
- [Microsoft SQL Docs](https://docs.microsoft.com/en-us/sql/sql-server/)
- [Microsoft Power BI Docs](https://learn.microsoft.com/en-us/power-bi/)

---

## 📬 Contact

Project by students at **Algonquin College – CST2102 Database Analytics**

Team Members:  
**Prajna Ganji**, **Shiva**, **Neetika Upadhyay**, **Maruta Zalane**

