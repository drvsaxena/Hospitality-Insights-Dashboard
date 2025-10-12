# 🏨 Hospitality Insights Dashboard

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-EE4C2C?style=for-the-badge&logo=dax&logoColor=white)

### *Data-Driven Hotel Performance Analytics*

[📊 View Live Dashboard](https://bit.ly/3HQmRgy)

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

</div>

---

## 🎯 Business Problem

The hospitality industry struggles with:
- ❌ Revenue leakage across multiple booking platforms
- ❌ Lack of real-time occupancy insights
- ❌ Poor visibility into guest satisfaction trends
- ❌ Inefficient booking channel performance tracking
- ❌ Limited competitive benchmarking capabilities

**Solution**: An interactive Power BI dashboard that transforms raw hotel data into actionable business intelligence.

---

## 📌 Objective

<div align="center">

```mermaid
graph TB
    A[📊 Raw Hotel Data] --> B{Power BI Dashboard}
    B --> C[📈 Monitor KPIs]
    B --> D[🏨 Compare Properties]
    B --> E[📊 Analyze Trends]
    B --> F[⭐ Track Satisfaction]
    B --> G[💡 Data-Driven Decisions]
    
    style A fill:#667eea,stroke:#764ba2,stroke-width:3px,color:#fff
    style B fill:#f093fb,stroke:#f5576c,stroke-width:4px,color:#fff
    style C fill:#4facfe,stroke:#00f2fe,stroke-width:2px,color:#fff
    style D fill:#43e97b,stroke:#38f9d7,stroke-width:2px,color:#fff
    style E fill:#fa709a,stroke:#fee140,stroke-width:2px,color:#fff
    style F fill:#30cfd0,stroke:#330867,stroke-width:2px,color:#fff
    style G fill:#a8edea,stroke:#fed6e3,stroke-width:2px,color:#fff
```

</div>

Build a comprehensive analytics dashboard to:
- 📈 Monitor key performance metrics (Revenue, RevPAR, ADR, Occupancy)
- 🏨 Compare property performance across cities
- 📊 Analyze booking trends and platform effectiveness
- ⭐ Track guest satisfaction and ratings
- 💡 Enable data-driven decision making for hotel management

---

## 🛠️ Tools & Technologies

<div align="center">

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard design & data visualization |
| **Power Query** | Data transformation & ETL |
| **DAX** | Advanced calculations & KPIs |
| **Data Modeling** | Star schema implementation |

<br>

```mermaid
journey
    title Data Analytics Journey
    section Data Collection
      CSV Files: 5: Power Query
      Excel Data: 5: Power Query
    section Transformation
      Clean Data: 4: Power Query
      Transform: 5: Power Query
    section Modeling
      Star Schema: 5: Data Model
      Relationships: 5: Data Model
    section Analytics
      DAX Measures: 5: DAX
      KPIs: 5: DAX
    section Visualization
      Dashboard: 5: Power BI
      Reports: 5: Power BI
```

</div>

---

## ✨ Key Features

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://via.placeholder.com/800x400/1e1e1e/ffffff?text=Dashboard+Features+Mindmap">
  <source media="(prefers-color-scheme: light)" srcset="https://via.placeholder.com/800x400/ffffff/000000?text=Dashboard+Features+Mindmap">
  <img alt="Dashboard Features" src="https://via.placeholder.com/800x400/ffffff/000000?text=Dashboard+Features+Mindmap">
</picture>

```mermaid
mindmap
  root((🏨 Dashboard))
    KPI Tracking
      Revenue
      RevPAR
      Occupancy %
      ADR
      Realization %
    Analytics
      Trend Analysis
      WoW Comparison
      Platform Performance
      City-wise Metrics
    Interactivity
      Dynamic Filters
      Custom Tooltips
      Drill-through
      Cross-filtering
```

<img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="600">

</div>

**Core Capabilities:**
- 🎯 **6 Key KPI Cards** with week-on-week change indicators
- 🗓️ **Multi-dimensional Filters**: Property, City, Platform, Month, Week
- 📊 **Revenue Distribution**: Platform-wise breakdown with donut chart
- 📈 **Trend Analysis**: Occupancy & ADR trends over time
- 📋 **Property Performance Matrix**: Detailed metrics for 25+ hotels
- 💬 **Interactive Tooltips**: Contextual insights on hover

---

## 📊 Key Performance Indicators

<div align="center">

```mermaid
%%{init: {'theme':'default'}}%%
quadrantChart
    title KPI Performance Matrix
    x-axis Low Impact --> High Impact
    y-axis Low Performance --> High Performance
    quadrant-1 Optimize
    quadrant-2 Maintain
    quadrant-3 Monitor
    quadrant-4 Improve
    Revenue: [0.85, 0.90]
    RevPAR: [0.75, 0.70]
    Occupancy: [0.60, 0.58]
    ADR: [0.80, 0.85]
    Realization: [0.70, 0.70]
    DSRN: [0.50, 0.65]
```

</div>

| Metric | Formula | Insight |
|--------|---------|---------|
| **Revenue** | Sum(revenue_realized) | Total earnings |
| **RevPAR** | Revenue ÷ Available Rooms | Revenue efficiency |
| **Occupancy %** | Rooms Sold ÷ Total Rooms × 100 | Capacity utilization |
| **ADR** | Revenue ÷ Rooms Booked | Average room rate |
| **DSRN** | Daily Sellable Room Nights | Inventory metric |
| **Realization %** | Revenue Realized ÷ Generated × 100 | Collection efficiency |

---

## 📸 Dashboard Preview

<div align="center">

![Main Dashboard](https://github.com/drvsaxena/Hospitality-Insights-Dashboard/blob/main/Hospitality-Insights/Screenshots/hotels_report.png?raw=true)

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

</div>

---

## 🏆 Key Achievements

<div align="center">

```
╔══════════════════════════════════════════════════════╗
║  💰  $1.69 Billion Revenue Analyzed                 ║
║  🏨  25+ Properties Monitored                       ║
║  📊  100K+ Booking Records Processed                ║
║  ⚡  96% Reduction in Reporting Time                ║
║  📈  70.14% Average Realization Rate                ║
╚══════════════════════════════════════════════════════╝
```

```mermaid
%%{init: {'theme':'forest'}}%%
xychart-beta
    title "Performance Metrics Overview"
    x-axis [Revenue, Occupancy, ADR, RevPAR, Realization]
    y-axis "Score (0-100)" 0 --> 100
    bar [95, 58, 85, 73, 70]
    line [90, 90, 90, 90, 90]
```

</div>

**Business Impact:**
✅ Reduced manual reporting from 4 hours to 10 minutes  
✅ Identified underperforming properties for optimization  
✅ Enabled platform-wise booking strategy  
✅ Real-time guest satisfaction monitoring  
✅ Data-driven revenue management decisions  

---

## 💡 Key Insights

<div align="center">

```mermaid
%%{init: {'theme':'neutral'}}%%
pie title Revenue Distribution by Booking Platform
    "Direct Offline 🏢" : 40.91
    "MakeYourTrip ✈️" : 19.85
    "LogTrip 🌐" : 18.82
    "Journey 🚗" : 10.34
    "Direct Online 💻" : 10.08
```

<br>

```mermaid
%%{init: {'theme':'base'}}%%
sankey-beta

Direct Offline,Revenue,691
MakeYourTrip,Revenue,335
LogTrip,Revenue,318
Journey,Revenue,175
Direct Online,Revenue,170
Revenue,Total Revenue,1689
```

</div>

- 📌 **Direct Offline** drives 40.91% of revenue (highest channel)
- 📌 **57.79% Average Occupancy** across all properties
- 📌 **₹12,696 ADR** indicates premium positioning
- 📌 **70.14% Realization** shows room for payment improvement
- 📌 **Delhi, Mumbai, Hyderabad, Bangalore** are key markets

---

## 🚀 Future Enhancements

- [ ] 🤖 **Predictive Analytics**: AI-based occupancy forecasting
- [ ] 💰 **Dynamic Pricing**: Smart rate recommendations
- [ ] 📱 **Mobile Dashboard**: Responsive design for on-the-go
- [ ] 🔔 **Automated Alerts**: Performance threshold notifications
- [ ] 🌐 **Real-time Integration**: Live PMS data connection
- [ ] 🎯 **Sentiment Analysis**: NLP on guest reviews

---

## 📁 Project Structure

```
Hospitality-Insights-Dashboard/
├── Data/
│   ├── dim_date.csv                      # Date dimension
│   ├── dim_hotels.csv                    # Property data
│   ├── dim_rooms.csv                     # Room types
│   ├── fact_bookings.csv                 # Booking transactions
│   ├── fact_aggregated_bookings.csv      # Aggregated metrics
│   └── metrics_list.xlsx                 # KPI definitions
├── Screenshots/
│   ├── hotels_report.png                 # Main dashboard
│   └── tooltip_*.png                     # Interactive tooltips
└── Hospitality.pbix                      # Power BI file
```

---

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="400">

### ⭐ Star this repo if you found it helpful!

**Made with Power BI 💙 and DAX magic ✨**

</div>
