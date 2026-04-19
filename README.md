## 📌 Project Overview

This project presents an **end-to-end logistics analytics solution** built using **Power BI**. The dashboard provides insights into delivery performance, driver efficiency, hub operations, and vehicle utilization.

The goal is to enable **data-driven decision-making** by identifying operational bottlenecks and improving delivery efficiency.

---

## 🎯 Business Objectives

* Monitor **On-Time Delivery Rate** and overall performance
* Track **Customer Satisfaction (CSAT %)**
* Analyze **Driver performance and delays**
* Evaluate **Hub capacity vs order processing**
* Optimize **Vehicle utilization and distribution**

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview

* Total Orders, On-Time Delivery %, CSAT %, Avg Delivery Time
* Month-over-Month (MoM) comparison
* High-level performance summary

![Executive Dashboard](https://github.com/Sasikumar-B7/Logistics-Dashboard-Power-BI-Report/blob/main/Home%20Page.png)

---

### 2️⃣ Drivers Overview

* Experience vs Performance Rating (Scatter Plot)
* Drivers with highest delays (Ranking)
* Individual driver deep dive:

  * Deliveries by month
  * Years of Experience
  * Performance rating (⭐ visual)

![Drivers Overview](https://github.com/Sasikumar-B7/Logistics-Dashboard-Power-BI-Report/blob/main/Drivers%20Hub.png)

---

### 3️⃣ Hubs Overview

* Orders Processed vs Hub Capacity
* Hub Performance Ranking
* Weekly processing time heatmap
* Identification of high-load hubs

![Hubs Overview](https://github.com/Sasikumar-B7/Logistics-Dashboard-Power-BI-Report/blob/main/Hubs%20Overivew.png)

---

### 4️⃣ Vehicles Overview

* Active vs Maintenance Vehicles (Donut Chart)
* Orders by Vehicle Model
* Vehicle age vs performance analysis
* Orders distribution by vehicle type

![Vehicles Overview](https://github.com/Sasikumar-B7/Logistics-Dashboard-Power-BI-Report/blob/main/Vehicles%20Overview.png)

---

## 🧩 Data Model

The dashboard is built using a **Star Schema Data Model** to ensure performance and scalability.

* **Fact Table**: Orders / Deliveries
* **Dimension Tables**:

  * Drivers
  * Hubs
  * Vehicles
  * Date Table

![Data Model](https://github.com/Sasikumar-B7/Logistics-Dashboard-Power-BI-Report/blob/main/Data%20Modelling.png)

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop**
* Power Query (Data Transformation)
* DAX (Data Analysis Expressions)
* Data Modeling (Star Schema)
* Interactive Visualizations

---

## 📈 Key Features

* ✔ Interactive slicers (Year, Month, Driver)
* ✔ Drill-down and navigation between pages
* ✔ KPI cards with previous month comparison
* ✔ Custom visual formatting and UI design
* ✔ Heatmap for operational analysis
* ✔ Ranking and performance segmentation

---

Good move—this is exactly what will differentiate your project. Right now your dashboard is strong visually, but **detailed insights = what makes recruiters take you seriously as an analyst**.

Below are **specific, data-backed insights** based on your screenshots. You can directly paste these into your README under **“Insights & Business Recommendations”** 👇

---

# 🧠 Detailed Insights & Business Recommendations

## 🚚 Overall Performance Insights (Executive Dashboard)

* **On-Time Delivery Rate: 78.6%** → indicates ~1 in 5 deliveries are delayed
  👉 This is a **significant operational gap** for a logistics company

* **Average Delivery Time increased by +4.5% MoM**
  👉 Suggests **efficiency decline**, possibly due to:

  * Hub overload
  * Driver inefficiencies
  * Vehicle availability issues

* **CSAT (82.6%) is relatively stable despite delays**
  👉 Customers may tolerate minor delays, but this could drop if trend continues

---

## 🧑‍✈️ Driver Performance Insights

### 📊 Experience vs Rating

* Drivers with **5–10 years experience cluster around ratings 4–5**
* However, some **mid-experience drivers (3–5 years)** show inconsistent ratings
  👉 Experience helps, but **not the only performance driver**

### ⏱️ Delay Analysis

* Top delayed drivers:

  * Mary Rodriguez (~45.5%)
  * Michael Williams (~43.8%)
  * Sarah Brown (~42.9%)

👉 These drivers consistently contribute to delays →
**Targeted intervention required (training / route optimization)**

### 🔍 Individual Driver Insight (Joseph Thompson)

* Completed **18 deliveries in June**
* Performance trend fluctuates across months (peaks ~22, dips ~16)
  👉 Indicates **inconsistent workload or route allocation**

### 💡 Recommendation

* Introduce **driver performance segmentation**:

  * High performers → assign critical deliveries
  * High-delay drivers → training / monitoring

---

## 🏭 Hub Performance Insights

### 📦 Capacity vs Orders

* **Houston Hub** operates near or above capacity
  👉 High risk of bottlenecks

* **Dallas Main Hub** shows better balance between capacity & orders
  👉 More stable operations

### 🏆 Hub Ranking

* Top performers:

  * Houston Hub (~83–84%)
  * Dallas Main Hub (~82–83%)

* Lowest:

  * Austin Hub (~70–72%)
    👉 Underperformance likely due to:
  * Lower efficiency
  * Resource constraints

### 📅 Weekly Processing Heatmap

* **Fort Worth Hub shows highest processing time (~41 hrs)**
  👉 Major inefficiency hotspot

* Most hubs show **consistent weekday load but reduced weekend activity**
  👉 Possible underutilization of weekends

### 💡 Recommendations

* Redistribute load from **Houston → Austin / El Paso**
* Optimize **Fort Worth processing workflows**
* Explore **weekend operations optimization**

---

## 🚛 Vehicle Utilization Insights

### 🔄 Active vs Maintenance

* **73% Active vs 27% in Maintenance**
  👉 Nearly **1 in 4 vehicles unavailable** → impacts delivery speed

### 🚚 Orders by Vehicle Model

* Top contributors:

  * Freightliner M2 (highest orders)
  * Ford Transit
  * Mercedes Sprinter

👉 Heavy dependency on few vehicle types → **risk concentration**

### 📉 Underutilized Vehicles

* Chevrolet Silverado / Isuzu NPR → low usage
  👉 Potential inefficiency in fleet allocation

### 📊 Vehicle Age vs Breakdown

* Older vehicles (6–8 years) show **higher breakdown frequency**
  👉 Strong correlation between **age and maintenance issues**

### 💡 Recommendations

* Reduce maintenance downtime via **preventive servicing**
* Replace high-breakdown older vehicles
* Rebalance usage across vehicle types

---

## 🔗 Cross-Functional Insights (Important for Interviews)

These are **gold-level insights recruiters love** 👇

### 🔁 Insight 1: Delays are multi-factor driven

* Not just drivers → also:

  * Hub overload (Houston)
  * Vehicle downtime (27% maintenance)

👉 Problem is **systemic, not isolated**

---

### 🔁 Insight 2: Bottleneck Chain

**Hub Overload → Increased Processing Time → Driver Delays → Lower On-Time Delivery**

👉 Clear operational chain identified

---

### 🔁 Insight 3: Efficiency Opportunity

* Some hubs underutilized (Austin)
* Some vehicles underused

👉 **Reallocation can improve performance without increasing cost**

---

## 🚀 Final Business Recommendations

* Improve **On-Time Delivery Rate from 78% → 90% target**
* Reduce **vehicle maintenance % from 27% → <15%**
* Implement **driver performance tracking system**
* Optimize **hub load balancing**
* Introduce **predictive maintenance for vehicles**
  
---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open using **Microsoft Power BI Desktop**
3. Use slicers (Year/Month/Driver) to explore insights
4. Navigate between pages using buttons

---

## 📌 Future Enhancements

* Add forecasting for delivery trends
* Implement What-If parameters for scenario analysis
* Integrate real-time data sources
* Add drill-through pages for deeper analysis

---

## 👤 Author

**Sasikumar B**
Data Analyst | BI Developer (Tableau & Power BI)

---

## ⭐ If you found this useful

Give this repository a ⭐ and feel free to connect!
