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
Hospitality-Insights_Dashboard/
        ├── Data/
        │   ├── dim_date.csv              # Date dimension table (3 KB)
        │   ├── dim_hotels.csv            # Hotel dimension data (1 KB)
        │   ├── dim_rooms.csv             # Room dimension data (1 KB)
        │   ├── fact_aggregated_bookings.csv  # Aggregated booking facts (240 KB)
        │   ├── fact_bookings.csv         # Detailed booking transactions (12,875 KB)
        │   └── metrics_list.xlsx         # Key performance metrics definitions (26 KB)
        ├── Screenshots/
        │   ├── hotels_report.png         # Hotel performance dashboard
        │   ├── tooltip_ADR.png           # Average Daily Rate tooltip
        │   ├── tooltip_occupancy.png     # Occupancy rate tooltip
        │   ├── tooltip_realization.png   # Realization percentage tooltip
        │   ├── tooltip_revenue.png       # Revenue metrics tooltip
        │   └── tooltip_revPAR.png        # Revenue per Available Room tooltip
        └── Hospitality.pbix              # Power BI dashboard file (2,296 KB)
```
---

## 🛠 Tech Stack
- **Power BI Desktop** – Dashboard design & modeling  
- **Power Query** – Data cleaning & transformation  
- **DAX (Data Analysis Expressions)** – Calculated measures & KPIs  
- **Excel/CSV** – Sample dataset  

---

## 📸 Dashboard Preview 
  ![Report](Screenshots/hotels_report.png)

---
