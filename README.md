# 📊 Berlin Bike Mobility Dashboard (Power BI)

## 📌 Project Overview
This project analyzes bicycle traffic data collected from permanent counting stations across Berlin.
The dashboard provides insights into overall bike volume, busiest stations, and station activation trends.

---

## 🗂️ Data Source
- **Radzähldaten in Berlin**
- Provided by the Berlin Open Data Portal
- Bicycle counts from permanent counting stations across the city

---

## 🛠️ Tools Used
- Power BI Desktop
- Power Query (data cleaning & transformation)
- Excel (raw data source)

---

## 🔄 Data Preparation Steps
- Combined multiple yearly Excel files
- Unpivoted wide tables into a tidy format
- Cleaned multiline text fields
- Split station code and commissioning date
- Removed invalid and null rows
- Created calculated aggregations for KPIs

---

## 📈 Dashboard Features
- Total bicycle count
- Average bikes per station
- Number of active bike counting stations
- Top 10 busiest bike counting stations
- Interactive filters by station and commissioning date

---

## 📷 Dashboard Preview

![Dashboard Overview](Screenshots/Berlin_Mobility_Project.pdf)

---

## 🚀 Future Improvements
- Add geographic map visualization
- Include weather data for trend analysis
- Extend analysis with time-based patterns

---

## 📁 Repository Structure
berlin-bike-mobility-dashboard/
│
├── dashboard/
│ └── Berlin_Bike_Mobility_Dashboard.pbix
├── screenshots/
└── README.md
