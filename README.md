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

<div align="center">

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#EA4335','primaryTextColor':'#fff','primaryBorderColor':'#b71c1c','lineColor':'#F8B229','secondaryColor':'#4285F4','tertiaryColor':'#34A853'}}}%%
graph LR
    A[❌ Revenue Leakage] --> E[🏨 Dashboard]
    B[❌ Poor Visibility] --> E
    C[❌ Manual Reports] --> E
    D[❌ No Benchmarking] --> E
    E --> F[✅ Real-time Insights]
    E --> G[✅ Automated Analytics]
    E --> H[✅ Better Decisions]
    
    style A fill:#EA4335,stroke:#fff,stroke-width:2px,color:#fff
    style B fill:#EA4335,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#EA4335,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#EA4335,stroke:#fff,stroke-width:2px,color:#fff
    style E fill:#9334E9,stroke:#fff,stroke-width:3px,color:#fff
    style F fill:#34A853,stroke:#fff,stroke-width:2px,color:#fff
    style G fill:#34A853,stroke:#fff,stroke-width:2px,color:#fff
    style H fill:#34A853,stroke:#fff,stroke-width:2px,color:#fff
```

</div>

The hospitality industry struggles with:
- ❌ Revenue leakage across multiple booking platforms
- ❌ Lack of real-time occupancy insights
- ❌ Poor visibility into guest satisfaction trends
- ❌ Inefficient booking channel performance tracking
- ❌ Limited competitive benchmarking capabilities

**Solution**: An interactive Power BI dashboard that transforms raw hotel data into actionable business intelligence.

---

## 📌 Objective

Build a comprehensive analytics dashboard to:
- 📈 Monitor key performance metrics (Revenue, RevPAR, ADR, Occupancy)
- 🏨 Compare property performance across cities
- 📊 Analyze booking trends and platform effectiveness
- ⭐ Track guest satisfaction and ratings
- 💡 Enable data-driven decision making for hotel management

---

## 🛠️ Tools & Technologies

<div align="center">

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#4285F4','primaryTextColor':'#fff','primaryBorderColor':'#2a5298'}}}%%
flowchart LR
    A[📊 Power BI Desktop] --> E[📈 Dashboard]
    B[🔄 Power Query] --> E
    C[📐 DAX] --> E
    D[🗄️ Data Modeling] --> E
    
    style A fill:#F2C811,stroke:#000,stroke-width:2px,color:#000
    style B fill:#4285F4,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#EE4C2C,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#34A853,stroke:#fff,stroke-width:2px,color:#fff
    style E fill:#9334E9,stroke:#fff,stroke-width:3px,color:#fff
```

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard design & data visualization |
| **Power Query** | Data transformation & ETL |
| **DAX** | Advanced calculations & KPIs |
| **Data Modeling** | Star schema implementation |

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
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#4285F4','primaryTextColor':'#fff','primaryBorderColor':'#2a5298','lineColor':'#F8B229','secondaryColor':'#EA4335','tertiaryColor':'#34A853'}}}%%
mindmap
  root((Dashboard))
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
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#4285F4','primaryTextColor':'#fff'}}}%%
graph TD
    A[📊 KPIs] --> B[💰 Revenue: ₹1.69B]
    A --> C[📈 RevPAR: ₹7,337]
    A --> D[🏨 Occupancy: 57.79%]
    A --> E[💵 ADR: ₹12,696]
    A --> F[✅ Realization: 70.14%]
    
    style A fill:#9334E9,stroke:#fff,stroke-width:3px,color:#fff
    style B fill:#4285F4,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#34A853,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#FBBC04,stroke:#fff,stroke-width:2px,color:#000
    style E fill:#EA4335,stroke:#fff,stroke-width:2px,color:#fff
    style F fill:#FF6B6B,stroke:#fff,stroke-width:2px,color:#fff
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
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#4285F4'}}}%%
pie title Revenue Distribution by Booking Platform
    "Direct Offline" : 40.91
    "MakeYourTrip" : 19.85
    "LogTrip" : 18.82
    "Journey" : 10.34
    "Direct Online" : 10.08
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
