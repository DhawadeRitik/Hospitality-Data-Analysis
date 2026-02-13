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

(Add dashboard screenshots here)

---

## 🛠 Tools & Technologies

- Power BI
- DAX
- SQL
- Data Modeling (Star Schema)
- Excel (Data Preparation)

---

## 📁 Repository Structure

