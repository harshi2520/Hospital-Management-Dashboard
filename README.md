# 🧾Hospital Emergency Dashboard using Power BI, Power Query, DAX

> Real-time hospital operations monitoring using Power BI, DAX, and Power Query

---

## 🚀 Project Overview

In today's fast-paced healthcare environment, efficient emergency room management is crucial. This project demonstrates a data-driven approach to improving hospital decision-making by building an interactive and scalable Power BI dashboard. It tracks 7,500+ patient records across 19 months, enabling leadership to monitor wait times, patient satisfaction, referral trends, and peak loads all in real time.

✅ Designed for stakeholders, operational managers, and hospital administrators.

✅ Built using real-world healthcare KPIs, advanced DAX, and responsive UX design.

---
## 🎯 Objectives

- Monitor emergency room performance with key KPIs
- Identify bottlenecks in patient wait times and admission processes
- Analyze demographic and departmental trends
- Optimize staffing based on peak hours and patient inflow
- Enable data-driven healthcare decisions
  
This dashboard addresses these challenges with a centralized, interactive reporting solution that helps improve service delivery, resource planning, and patient experience.

---
## 📊 Key KPIs (Important Numbers We Track)

These KPIs help monitor operational performance and identify improvement areas.

| KPI Name                | What It Tells Us |
|-------------------------|------------------|
| **Number of Patients**      | Total volume of ER patients in the selected period. |
| **Average Wait Timee** | Average time patients waited before being seen. |
| **Patient Satisfaction Score**  | How satisfied patients were with their ER experience. |
| **Number of Patients Referred**       | How many patients were referred to other departments or specialists. |
| **% of Patients Seen Within 30 Minutes**   | How quickly patients were triaged and treated compared to the target benchmark. |
| **Admission Status** | The split between admitted vs. non-admitted cases. |

🧠 **Why These Matter Together**:
- They help pinpoint operational bottlenecks (long wait times, poor satisfaction).
- Identify peak hours and days to improve staffing.
- Show progress towards compliance targets (e.g., seeing patients within 30 minutes).
- Support decisions about resource allocation and workflow changes.

---

## 🖼️ Dashboard Snapshots

### 📄 1. Monthly View

A focused view for analyzing any specific month.

✅ Highlights:

- Daily trends in patient counts, wait times, and satisfaction.
- Admission and referral metrics.
- Demographics filtered for the selected month.
- Hourly heatmap for operational insights.

![Monthly View](https://github.com/harshi2520/Hospital-Management-Dashboard/blob/main/Montly%20View.png)

---

### 📄 2. Holistic View

An overall, high-level summary of emergency department performance across all available data.

✅ Highlights:

- Monthly trends in patient volume, wait time, and satisfaction.
- Total counts of admitted and referred patients.
- Age group, gender, and race demographics.
- A heatmap of arrivals by day and hour.

![Consolidated View](https://github.com/bhumikabharadwaj2205/Hospital-Management-Dashboard/blob/main/Consolidated%20View.png)

---

### 📄 3. Patient Details

A tabular view of patient-level data:
- Shows detailed records with fields like Patient Name, Age, Gender, Admission Date, Race, Referral Department, and Admission Status
- Filterable by date and other attributes for deeper analysis
- Useful for audits and internal reviews.

![Patient Details](https://github.com/bhumikabharadwaj2205/Hospital-Management-Dashboard/blob/main/Monthly%20View.png)

---

### 🧠 4. Summary

A narrative-based summary generated from insights:
- Highlights top trends in wait times, referrals, admission behavior, and demographics
- Written in natural language, useful for stakeholders who prefer summaries over visuals
- Supports strategic planning and performance reviews

![Summary](https://github.com/bhumikabharadwaj2205/Hospital-Management-Dashboard/blob/main/Monthly%20View.png)

---

## 📘 Key DAX Insight: % of Patients Seen Within 30 Minutes

As part of building this dashboard, I created a DAX measure to track how effectively the ER meets its triage benchmark.

### 📌 DAX Formula


### 🖼️ Screenshot: % of Patients Seen Within 30 Minutes

![C](https://github.com/bhumikabharadwaj2205/Hospital-Management-Dashboard/blob/main/Formula.png))


### 🧮 What the Formula Does

- Numerator: Counts patients whose wait time was 30 minutes or less.
- Denominator: Counts all patients.
- DIVIDE: Returns the percentage safely, avoiding divide-by-zero errors.

📊 **For example**:  
If 4,500 out of 7,500 patients were seen within 30 minutes, the KPI would show 60%.

