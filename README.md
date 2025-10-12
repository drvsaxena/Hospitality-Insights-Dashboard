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

</div>

---

## ✨ Key Features

<div align="center">

```mermaid
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

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/drvsaxena/Hospitality-Insights-Dashboard.git
   ```

2. **Open in Power BI Desktop**
   - Launch Power BI Desktop
   - Open `Hospitality.pbix`
   - Click Refresh to load data

3. **Explore the Dashboard**
   - Use left-panel filters to slice data
   - Hover over visuals for detailed insights
   - Click charts for cross-filtering

4. **View Online**
   - 🌐 [Access Live Dashboard](https://bit.ly/3HQmRgy)

---

## 👨‍💻 Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/drvsaxena)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="400">

### ⭐ Star this repo if you found it helpful!

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=drvsaxena.Hospitality-Insights-Dashboard)

**Made with Power BI 💙 and DAX magic ✨**

</div>
