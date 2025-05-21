# 📦 Supply Chain Performance Analysis – AtliQ Mart

## 🧭 Overview
This project focuses on analyzing and monitoring **supply chain delivery performance** for **AtliQ Mart**, a growing FMCG manufacturer based in Gujarat, India. The company operates in **Surat**, **Ahmedabad**, and **Vadodara**, with plans to expand to Tier-1 cities across India.

Due to recent customer churn—likely driven by poor delivery experiences—the **management requested a robust analysis of their delivery service levels**, particularly focusing on:
- **On-Time Delivery (OT%)**
- **In-Full Delivery (IF%)**
- **On-Time In-Full (OTIF%)**

The goal is to **identify service gaps**, **track performance trends**, and **enable data-driven decision-making** before expansion.

---

## 📌 Problem Statement
AtliQ Mart is losing key customers due to **suspected delivery failures**. Essential products were not delivered **on time** or **in full**, leading to **poor service perception**.

To address this, the supply chain analytics team must:
- Track service KPIs (OT%, IF%, OTIF%) **on a daily basis**
- Monitor performance **per customer**
- Compare against **target service levels**
- Enable timely intervention using visual dashboards

---

## 🧰 Tools & Technologies
- **Power BI** for data visualization and dashboarding
- **Microsoft Excel / CSV** as data source
- **DAX (Data Analysis Expressions)** for calculated metrics
- **Power Query** for data transformation
- **KPIs**: OT%, IF%, OTIF%

---

## 📊 Key Metrics Explained
| Metric | Description |
|--------|-------------|
| **On-Time % (OT%)** | Percentage of orders delivered on or before the promised date |
| **In-Full % (IF%)** | Percentage of orders delivered completely with no shortfall |
| **OTIF %**          | Percentage of orders delivered both on time and in full |

---

## 📈 Dashboard Features
- 📅 **Daily and Monthly Trend Analysis**
- 🧾 **Customer-wise Service Level Monitoring**
- 🎯 **Target vs Actual Performance**
- 🧭 **Root Cause Indicators** for poor OTIF
- ⚠️ **Dynamic Filters**: Customer, Product, City, Date range

---

## 🧩 Data Model

Understanding the data model is crucial for interpreting the service-level metrics accurately. The relationships between the fact and dimension tables ensure that filters, aggregations, and KPIs behave as expected across visuals.

<p align="center">
  <img width="727" alt="Power BI Data Model" src="https://github.com/user-attachments/assets/d17c84f1-1eb9-4b18-81da-a3e4f22eae40">
</p>

---

## 🚀 How to Use
1. Open the `.pbix` file in **Power BI Desktop**
2. Refresh the data connection
3. Explore dashboards using slicers and filters
4. Export visuals or publish to Power BI Service as needed
