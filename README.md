# 🚗 Uber Ride Demand Analysis — New York City (2014)

> A Python-based data analysis project exploring **temporal and spatial ride demand patterns** for Uber pickups in New York City.  
> The goal: derive actionable insights to help optimize driver allocation and operational efficiency.

---

## 🎯 Objective

To analyze and visualize how **Uber ride demand** varies across different **hours, days, and locations**, and to uncover patterns that can guide better decision-making for fleet management and resource distribution.

---

## 📊 Dataset — Uber Pickups in NYC (FiveThirtyEight)

**Source:** [Kaggle – Uber Pickups in NYC (2014)](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city)  
**Records:** ~4.5 million rides (April–September 2014)

| Column | Description |
|---------|-------------|
| `Date/Time` | Timestamp of each pickup |
| `Lat`, `Lon` | Pickup location coordinates |
| `Base` | Affiliated base/company code |

---

## ⚙️ Tech Stack

| Category | Tools |
|-----------|--------|
| 🐍 Language | Python |
| 🧮 Data Analysis | pandas, numpy |
| 🎨 Visualization | matplotlib, seaborn |
| 📘 Notebook | Jupyter / Google Colab |

---

## 🧹 Data Preparation

- Loaded and merged monthly ride data (April–September 2014)  
- Extracted **hour**, **weekday**, and **month** from timestamp  
- Handled missing values and unified column formats  
- Created time-based and spatial aggregations using pandas  

---

## 🔍 Exploratory Analysis

### ⏰ Temporal Trends
- **Hourly demand:** Identified sharp evening peaks between **5–9 PM**  
- **Day-of-week:** Fridays and Saturdays show **30% higher night demand**  
- **Monthly:** Steady growth from April → September as Uber’s usage expanded  

### 📆 Weekday vs Hour Heatmap
Visualized combined hourly and daily trends to reveal dual-peak structure:  
morning (7–9 AM) and evening (5–9 PM) commute rush.

### 📍 Geospatial Demand
- KDE plots show pickup clusters around **Manhattan and Brooklyn**  
- Sparse activity in outer boroughs and early-morning hours  

---

## 📈 Results

| Metric | Observation |
|:--------|:-------------|
| Peak Hours | 5 PM – 9 PM |
| Busiest Days | Friday, Saturday |
| Lowest Activity | 3 AM – 5 AM |
| Hotspot | Manhattan (Midtown & Downtown) |

---


---

## 💡 Key Insights

- Evening hours show **double the demand** compared to early mornings.  
- Friday and Saturday nights dominate late-night bookings.  
- Spatial data confirms **urban-core concentration** of pickups.  
- Temporal-spatial analysis supports **driver shift optimization** during rush hours.

---

## 🧰 Folder Structure
