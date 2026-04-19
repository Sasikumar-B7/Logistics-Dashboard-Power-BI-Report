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

📸 *Screenshot Placeholder:*
![Executive Dashboard](images/executive_dashboard.png)

---

### 2️⃣ Drivers Overview

* Experience vs Performance Rating (Scatter Plot)
* Drivers with highest delays (Ranking)
* Individual driver deep dive:

  * Deliveries by month
  * Years of Experience
  * Performance rating (⭐ visual)

📸 *Screenshot Placeholder:*
![Drivers Overview](images/drivers_overview.png)

---

### 3️⃣ Hubs Overview

* Orders Processed vs Hub Capacity
* Hub Performance Ranking
* Weekly processing time heatmap
* Identification of high-load hubs

📸 *Screenshot Placeholder:*
![Hubs Overview](images/hubs_overview.png)

---

### 4️⃣ Vehicles Overview

* Active vs Maintenance Vehicles (Donut Chart)
* Orders by Vehicle Model
* Vehicle age vs performance analysis
* Orders distribution by vehicle type

📸 *Screenshot Placeholder:*
![Vehicles Overview](images/vehicles_overview.png)

---

## 🧩 Data Model

The dashboard is built using a **Star Schema Data Model** to ensure performance and scalability.

* **Fact Table**: Orders / Deliveries
* **Dimension Tables**:

  * Drivers
  * Hubs
  * Vehicles
  * Date Table

📸 *Data Model View Placeholder:*
![Data Model](images/data_model.png)

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

## 🧠 Key Insights

* Some hubs operate close to capacity, indicating potential bottlenecks
* Drivers with higher experience generally show better performance ratings
* Certain vehicle models contribute disproportionately to total deliveries
* Delay patterns highlight specific drivers needing performance improvement

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open using **Microsoft Power BI Desktop**
3. Use slicers (Year/Month/Driver) to explore insights
4. Navigate between pages using buttons

---

## 📂 Repository Structure

```bash
/images
   executive_dashboard.png
   drivers_overview.png
   hubs_overview.png
   vehicles_overview.png
   data_model.png

SwiftRoute_Dashboard.pbix
README.md
```

---

## 📌 Future Enhancements

* Add forecasting for delivery trends
* Implement What-If parameters for scenario analysis
* Integrate real-time data sources
* Add drill-through pages for deeper analysis

---

## 👤 Author

**Sasikumar B**
Data Analyst | Power BI Developer

---

## ⭐ If you found this useful

Give this repository a ⭐ and feel free to connect!

---

If you want, I can next:

* Write a **killer LinkedIn post for this project**
* Or create **interview Q&A based on your dashboard (very useful for PL-300 + jobs)**
