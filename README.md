# 🚕 Project-1-Uber-Data-Analysis-
An in depth  **data anlaytics and visualization project** built by using **Python (EDA)** and **Power BI** , amied at analyzing Uber ride data in the NCR region to uncover trends in booking ,revenue, cancellation, and performance.

---
## 📘 Project Overview 
This project focus on understanding the key aspects of uber's business operations by analyzing the ride data .
It helps to answer the following question :
- What is the peak time and month in terms of rides and revenue?
- What are the top reasons for cacellation?
- Who cancelles the ride most customers or drivers?
- How does revenue vary by vehicle type and payment method?
- How do customers rating and driver rating compare?

---
## 📁 Dataset Details 

 - Source : **https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard?select=ncr_ride_bookings.csv
 - Rows : Over 15,000
 - Columns Name : Date , Time , Booking ID , Customer ID , AVG VTAT, AVG CTAT , Ride Distance , Booking Status , Vehicle Type , Pickup locations and Drop locations , Cancelled by driver , Reason for cancellation by driver , Cancelled by customers , Reason for cancellation by customers , Booking value , Payment method , Driver rating , Customer rating

---
## 🧹 Data Cleaning and EDA (Python)
All the preprocessing and expolatory analysis were done i the python using **pandas , numpy , matplolib and seaborn**

### Steps Performed :
- Handelled the missing values by filling them using mean/mode in the numeric columns.
- Handelled the missing values by filling **Unknown** in the string columns.
- Converted the data types of the columns.
- Done some feature engineering by adding new columns like **Rush Hour** , **Time of day**, **Month Name** and **Day**
- Gathered insights by performing some basics visuaization in EDA
- Generated summary satistics using **describe()** and **Correlation analysis**.

---

## 📊 Dashboards and Features 
**1. Overview Dashboard**

<img width="1095" height="725" alt="Overview" src="https://github.com/user-attachments/assets/3e073dfb-608b-4390-add2-d3631083855e" />

**Features:**

**KPI'S:**
- Total Booking Value: 6.03 cr
- Total Bookig: 150k
- Average Ride Distance: 20KM
- Average Custumer Rating: 4.36
- Cancellation Rate: 0.62

**Charts And Visualizatiion:**
- Line Chart: Number of ride per month in the year 2024(Peak rides in May, June and Jan)
- Pie Chart: Total rides by the vehchile type(Auto: 20% and Go mini: 20%)
- Bar Chart: Status of the rides(over 93k are completed)
- Doughnut Chart: Payment Method(UPI: 62%)

---

**2. Booking Trend**

<img width="1083" height="726" alt="Booking Analysis" src="https://github.com/user-attachments/assets/c6814a23-def3-4273-8fe1-65fe77db7ebf" />

**Features:**

**KPI'S:**
- Average Fare Price: 402 RS
- Average Trip Durtion: 29.10 MIN
- Average Ride Distance: 20 KM
- Average Wait Time : 9 MIN


**Charts And Visualization:**
- Stacked Column Charts: Booking trend by month weekday VS weekend (Weekdays are more dominants in term of booking where weekends are not)
- Pie Chart: Total rides by the vehchile type(Auto: 20% and Go mini: 20%)
- Map Chart; Most common pickup locations
- Column Chart: Booking in what time of day(Late night: 54K)

---

 
 
