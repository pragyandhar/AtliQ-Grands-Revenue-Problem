# 🏨 AtliQ Grands Revenue Problem - Power BI Resume Challenge Project

Welcome to my Power BI project for the Codebasics Resume Challenge!  
This project focuses on solving a real-world business case for **AtliQ Grands**, a chain of luxury and business hotels across India, using **Power BI**.

---

## 📌 Problem Statement

AtliQ Grands has been a key player in the Indian luxury and business hotel market for the past 20 years. Recently, due to increasing competition and poor data-driven decision-making, they have experienced a decline in market share and revenue.

The management is now looking to incorporate **Business and Data Intelligence** to reverse this trend. However, they lack an internal analytics team and have hired a third-party service (a.k.a. *Me*) to extract insights from their historical data.

---

## 📂 Data Overview

The dataset consists of 5 CSV files, split into dimensions and facts:

### 🔹 Dimension Tables
1. **`dim_date.csv`**
   - `date`: Specific date (May–July)
   - `mmm yy`: Month-Year format
   - `week_no`: Unique week number
   - `day_type`: Weekend or Weekday

2. **`dim_hotels.csv`**
   - `property_id`: Unique hotel ID
   - `property_name`: Hotel name
   - `category`: Hotel class (Luxury/Business)
   - `city`: Hotel location

3. **`dim_rooms.csv`**
   - `room_id`: Room type (RT1–RT4)
   - `room_class`: Room category (Standard to Presidential)

---

### 🔸 Fact Tables
4. **`fact_aggregated_bookings.csv`**
   - `property_id`: Hotel ID
   - `check_in_date`: Date of check-in
   - `room_category`: Room type
   - `successful_bookings`: Number of bookings
   - `capacity`: Max available rooms

5. **`fact_bookings.csv`**
   - `booking_id`: Unique booking ID
   - `property_id`: Hotel ID
   - `booking_date`: Date of booking
   - `check_in_date`: Check-in date
   - `check_out_date`: Check-out date
   - `no_guests`: Number of guests
   - `room_category`: Room type
   - `booking_platform`: Booking source
   - `ratings_given`: Customer rating
   - `booking_status`: Booking outcome (Cancelled / Checked Out / No Show)
   - `revenue_generated`: Gross revenue
   - `revenue_realized`: Net revenue after adjustments

---

## 📊 Project Goal

To develop an interactive Power BI dashboard that:
- Identifies trends in bookings and revenue  
- Highlights underperforming properties  
- Compares room types and customer behavior  
- Recommends data-driven strategies for growth

---

## 🛠 Tools & Skills Used

- **Power BI** (Data Modeling, DAX, Visuals)
- **Excel** (Data Cleaning)
- **Problem Solving & Business Insight**
- **Storytelling with Data**

---

## 💡 Outcome

The final Power BI dashboard delivers a strategic overview for AtliQ Grands’ leadership, aiding better decision-making across cities, room types, and revenue channels.

---

## 🧠 Credits

Inspired by the [Codebasics Resume Projects](https://www.codebasics.io/), an excellent initiative to build portfolio-ready analytics projects.

---

## 📬 Connect With Me

📧 Drop a message if you'd like to collaborate or discuss data!  
🚀 *More Power BI projects on the way... stay tuned!*

