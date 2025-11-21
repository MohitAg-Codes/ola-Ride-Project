# 🚖 OLA Ride Data Analytics Project

## 📘 Overview
This project demonstrates an end-to-end **data analytics workflow** on OLA ride bookings.  
It covers data cleaning in Excel, SQL analysis using MySQL, dashboard creation in Power BI, and generating key business insights.

The goal is to analyze booking patterns, cancellations, revenue distribution, and customer/driver ratings.

---

## 📂 Dataset
The dataset contains one month of OLA ride bookings for Bengaluru.

### **Key Columns**
- Booking ID  
- Date & Time  
- Vehicle Type  
- Booking Status  
- Payment Method  
- Ride Distance  
- Booking Value  
- Customer Rating  
- Driver Rating  
- Cancellation Reason  

### **Project Files**
- Raw Excel Dataset  
- SQL File: `ola-bookings.sql`  
- Power BI File: `ola-bookings.pbix`

---

## 🛠️ Tools & Technologies
- **Excel** – Data Cleaning  
- **MySQL Workbench** – SQL Queries  
- **Power BI** – Dashboard & KPIs  
- **DAX** – Measures  

---

## 🔧 Steps Performed

### 1️⃣ Data Cleaning in Excel
- Removed duplicates  
- Standardized Date & Time  
- Cleaned text values  
- Fixed inconsistent category labels  
- Checked numeric fields (value, ratings, distance)  

### 2️⃣ SQL Analysis in MySQL
Ran SQL queries to extract insights such as:
- Total vs Successful Bookings  
- Average ride distance per vehicle type  
- Top 5 customers  
- Driver cancellation reasons  
- Revenue from completed rides  
- Customer rating by vehicle type  

SQL queries are included in:  
`ola-bookings.sql`

### 3️⃣ Power BI Dashboard Development

#### 📊 **Overall Summary Dashboard**
- Total Bookings  
- Successful Booking Value  
- Booking Status Breakdown  
- Ride Volume Trend  
![Overall](Overall.png)

---

#### 🚗 **Vehicle Type Dashboard**
- Bookings by Vehicle Category  
- Revenue Distribution  
- Ratings Comparison  
![Vehicle Type](Vehicle%20Type.png)

---

#### 💰 **Revenue Dashboard**
- Total Revenue  
- Revenue by Vehicle Type  
- Revenue Trend Line  
![Revenue](Revenue.png)

---

#### ❌ **Cancellation Dashboard**
- Driver vs Customer Cancellation  
- Cancellation Reasons  
- Cancellation Trends  
![Cancellation](Cancellation.png)

---

#### ⭐ **Ratings Dashboard**
- Driver Ratings  
- Customer Ratings  
![Ratings](Ratings.png)

---

## 📈 Key Insights
- **62%** of rides completed successfully  
- **Driver-related cancellations:** ~18%  
- **Prime Plus & Prime Sedan** had the best overall ratings  
- Weekends and mid-month days had higher booking volume  
- Successful rides generated approx **₹7M** booking value  

---

## ▶️ How to Run This Project

### **1. Excel**
- Download dataset  
- Open in Excel  
- Perform basic cleaning  

### **2. MySQL**
- Create database  
- Import dataset  
- Run SQL queries from `ola-bookings.sql`  

### **3. Power BI**
- Open `ola-bookings.pbix`  
- Click **Refresh**  
- Explore all dashboards  

---


