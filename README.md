# 🚲 Cyclistic Bike-Share Analysis

## 📌 Case Study: "How Does a Bike-Share Navigate Speedy Success?"

This is a portfolio project for analyzing usage differences between **casual riders** and **annual members** for the Cyclistic bike-share program in Chicago. The goal is to uncover patterns that can support marketing efforts to convert casual users into annual members.

---

## 🎯 Business Task

Understand how annual members and casual riders use Cyclistic bikes differently, and provide data-driven recommendations to increase annual memberships.

---

## 🧠 Key Questions

1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

---

## 📊 Dataset

- Source: [Divvy Trip Data (via Motivate)](https://divvy-tripdata.s3.amazonaws.com/index.html)
- Data: Public bike trip data from the last 12 months
- Format: CSV files (each month)

> Note: Personal information has been removed to ensure privacy.

---

## 🛠 Tools Used

- R and RStudio (or Python)
- tidyverse / dplyr / ggplot2 (or pandas / matplotlib)
- Excel (optional)
- GitHub for version control

---

## 🧹 Data Cleaning Summary

- Removed null and duplicate values
- Converted time columns to proper datetime formats
- Filtered out trips <1 minute or >24 hours
- Created new features: day_of_week, ride_length, month

---

## 📈 Key Findings

- **Casual riders** take longer rides, mainly on **weekends**
- **Members** take shorter, more frequent rides, mostly on **weekdays**
- Certain stations are more popular with one group over the other

---

## 📌 Recommendations

1. **Launch weekend membership discounts** to encourage conversion of casual users.
2. **Target commuting routes** with benefits messaging for members.
3. **Use digital campaigns** on high-casual-use days (Saturdays/Sundays).

---

## 📸 Visualizations

(You can insert image files or links here — examples below:)

- ![Ride Duration by User Type](images/ride_duration.png)
- ![Weekly Usage Trends](images/weekly_trends.png)

---
## Analysis Summary

To analyze Cyclistic bike-share usage, I followed the structured data analysis process using Excel. I worked with two cleaned datasets covering multiple months, merged them into a single file, and calculated the following key metrics:

- **ride_length**: Calculated by subtracting `started_at` from `ended_at` for each ride.
- **day_of_week**: Extracted using Excel's `WEEKDAY()` function to analyze weekly trends.

I conducted descriptive analysis using pivot tables:

- **Average ride length** for members vs. casual riders
- **Number of rides** by member type and day of the week
- **Average ride length** by day of the week

These insights allowed me to identify usage patterns that can inform marketing strategies aimed at converting casual riders into annual members.


