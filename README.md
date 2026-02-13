# 🏨 Hospitality Revenue & Performance Analytics Dashboard

Power BI | DAX | SQL | End-to-End Business Intelligence Project

---

## 📌 Project Summary

This project is an end-to-end Hospitality Business Intelligence solution designed to analyze hotel revenue performance, booking trends, occupancy behavior, and capacity utilization across multiple cities and properties.

The solution demonstrates a complete BI workflow:

Data Validation (SQL) → Data Modeling (Star Schema) → KPI Engineering (DAX) → Executive Dashboarding (Power BI)

The dashboard enables business stakeholders to monitor financial performance, optimize pricing strategies, and reduce revenue leakage caused by cancellations and no-shows.

---

## 📊 Key KPIs Implemented

- Total Revenue
- ADR (Average Daily Rate)
- RevPAR (Revenue per Available Room)
- DSRN (Daily Sellable Room Nights)
- Occupancy %
- Realisation %
- Cancellation Rate %
- No-Show Rate %
- Week-over-Week (WoW) Growth %

Each KPI includes:
- Current value
- WoW % change
- Trend indicators (increase/decrease arrows)
- Dedicated Tooltip Page for detailed drill-down analysis

---

## 🧠 Technical Implementation

### 🔹 Data Model
Designed a Star Schema Data Model:

- Fact Tables:
  - fact_bookings
  - facts_aggregated_bookings
- Dimension Tables:
  - dim_hotels
  - dim_rooms
  - dim_date

Implemented proper one-to-many relationships and optimized filter propagation.

---

### 🔹 DAX Engineering

Created advanced DAX measures including:

- RevPAR = Revenue / Available Rooms
- ADR = Revenue / Rooms Sold
- Occupancy % = Rooms Sold / Total Capacity
- Realisation % = Realized Revenue / Generated Revenue
- Cancellation %
- No-Show %
- WoW % Growth Calculation using Date Intelligence

---

## 📈 Dashboard Analysis Includes

### 1️⃣ Revenue Performance
- Revenue by Property
- Revenue by Category (Luxury vs Business)
- Revenue Trend Analysis

### 2️⃣ Booking & Capacity Analysis
- Booking vs Capacity by Property
- Booking vs Capacity by Room Type
- Booking vs Capacity by Day Type (Weekday vs Weekend)
- Booking vs Capacity by Category

### 3️⃣ Trend Monitoring
- ADR Trend
- RevPAR Trend
- Occupancy % Trend
- WoW RevPAR % Change by Week

### 4️⃣ Platform Performance
- Realisation % by Booking Platform
- ADR by Platform

---

## 🛠 Interactive Features

- Dynamic Filters (City, Room Type, Month)
- KPI Tooltip Pages:
  - Revenue Tooltip
  - RevPAR Tooltip
  - ADR Tooltip
  - DSRN Tooltip
  - Occupancy % Tooltip
  - Realisation % Tooltip
- Drill-down & slicer functionality
- Conditional formatting for performance indicators

---

## 💡 Business Impact

- Identified high-revenue properties
- Detected revenue leakage from cancellations and no-shows
- Compared weekday vs weekend occupancy behavior
- Analyzed room-class profitability
- Evaluated capacity utilization efficiency
- Enabled data-driven pricing and demand optimization

---

## 📷 Dashboard Preview

<img width="1278" height="705" alt="image" src="https://github.com/user-attachments/assets/5f176c13-e1d4-48f5-aa44-99cff8b941c5" />

<img width="1143" height="683" alt="image" src="https://github.com/user-attachments/assets/9c42c951-b724-410a-9a1e-a120a6fee168" />

<img width="1067" height="597" alt="image" src="https://github.com/user-attachments/assets/5a2bd520-0362-484a-adc7-b9b2a1265ca9" />

<img width="1005" height="601" alt="image" src="https://github.com/user-attachments/assets/6ced6450-e63e-4bc6-b611-79571b24af14" />

<img width="998" height="620" alt="image" src="https://github.com/user-attachments/assets/b088e6c9-c772-4663-b7f1-1ffaae145f69" />

<img width="1053" height="608" alt="image" src="https://github.com/user-attachments/assets/51b59118-6715-4209-b9f5-e68b452d75c3" />

<img width="930" height="591" alt="image" src="https://github.com/user-attachments/assets/117584c0-4a9e-4db5-a0d1-a9b0662d49bd" />

<img width="978" height="587" alt="image" src="https://github.com/user-attachments/assets/093062c7-9833-4294-b6cc-425767f5870f" />


---

## 🛠 Tools & Technologies

- Power BI
- DAX
- SQL
- Data Modeling (Star Schema)
- Excel (Data Preparation)

---

## 📁 Repository Structure

