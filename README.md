# 🏨 Hospitality Insights Dashboard

## 🌐 Live Dashboard
👉 [View the interactive dashboard](https://bit.ly/3HQmRgy)

---

## 📌 Overview
This project is an **interactive Power BI dashboard** built for the hospitality domain.  
It analyzes hotel performance across **bookings, occupancy, revenue, and guest experience**.  

The dashboard leverages **Power Query** for ETL, **DAX measures** for KPIs, and **data modeling** to connect different datasets for meaningful insights.

---

## ✨ Features
- **KPI Tracking**: Occupancy %, Revenue, ADR, RevPAR, Average Rating  
- **Trend Analysis**: Occupancy & revenue by month/season  
- **Booking Sources**: OTA vs. Website vs. Walk-ins  
- **Guest Experience**: Ratings and satisfaction index  

---

## 📂 Project Structure
```
Hospitality-Insights-Dashboard/
├── Data/
│   ├── dim_date.csv              # Date dimension table
│   ├── dim_hotels.csv            # Hotel dimension data
│   ├── dim_rooms.csv             # Room dimension data
│   ├── fact_aggregated_bookings.csv  # Aggregated booking facts
│   ├── fact_bookings.csv         # Detailed booking transactions
│   └── metrics_list.xlsx         # Key performance metrics definitions
├── Screenshots/
│   ├── hotels_report.png         # Hotel performance dashboard
│   ├── tooltip_ADR.png           # Average Daily Rate tooltip
│   ├── tooltip_occupancy.png     # Occupancy rate tooltip
│   ├── tooltip_realization.png   # Realization percentage tooltip
│   ├── tooltip_revenue.png       # Revenue metrics tooltip
│   └── tooltip_revPAR.png        # Revenue per Available Room tooltip
└── Hospitality.pbix              # Power BI dashboard file
```
---

## 📸 Dashboard Preview 
![Report](https://github.com/drvsaxena/Hospitality-Insights-Dashboard/blob/main/Hospitality-Insights/Screenshots/hotels_report.png?raw=true)

---

## 🛠 Tech Stack
- **Power BI Desktop** – Dashboard design & modeling  
- **Power Query** – Data cleaning & transformation  
- **DAX (Data Analysis Expressions)** – Calculated measures & KPIs  
- **Excel/CSV** – Sample dataset  

---
