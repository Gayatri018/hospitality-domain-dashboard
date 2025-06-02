# End-to-End Revenue Insights in Hospitality Domain

## 📌 Project Overview
This project aims to extract actionable insights from a hospitality domain dataset using Power BI. It provides end-to-end visibility—from data import and transformation to advanced DAX measures and an interactive dashboard. This enables stakeholders to monitor revenue performance, booking trends, cancellations, and occupancy.

---

## 🔄 Flow of Work

Data Source → Power Query → DAX → Dashboard


---

## ✅ Steps Followed

1. **Imported Data**  
   Loaded the data folder containing all necessary files into Power BI.

2. **Data Transformation**  
   Cleaned and transformed raw data using **Power Query**—applied filters, renamed columns, fixed data types.

3. **DAX Columns & Measures**  
   After data load, used **DAX (Data Analysis Expressions)** to:
   - Add calculated columns (e.g., Weekend/Weekday classification).
   - Create new measures for aggregation and KPIs.

4. **Data Modeling**  
   Created a **star schema** by establishing proper relationships among fact and dimension tables for optimal performance and data normalization.

5. **Dashboard Development**  
   Built an interactive dashboard using slicers, cards, charts, and visuals to present KPIs clearly and effectively.

---

## 📊 Key DAX Measures Created

- `Revenue = SUM('Table'[Revenue Realized])`
- `Total Bookings = COUNT('Table'[Booking ID])`
- `Total Capacity = SUM('Table'[Capacity])`
- `Total Successful Bookings`
- `Occupancy % = (Successful Bookings / Total Capacity) * 100`
- `Average Booking`
- `Number of Days in Data`
- `Total Cancellation Bookings`
- `Cancellation % = (Cancellations / Total Bookings) * 100`
- `Total Checked Out`
- ... and more

---

## 🧩 Visual Assets

### 📌 Mock-up Dashboard  
![Mockup Dashboard](images/mockup%20dashboard.png)

### 📌 Data Model  
![Data Model](images/data%20model.png)

### 📌 Final Dashboard  
![Final Dashboard](images/my%20dashboard.png)


---

## 🛠 Tools & Technologies
- **Power BI**
- **Power Query (M Language)**
- **DAX (Data Analysis Expressions)**
- **Star Schema Modeling**

---

