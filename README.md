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
 
 
