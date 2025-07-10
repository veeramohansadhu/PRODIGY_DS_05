# 🚦 Traffic Accident Data Analysis

## 📝 Task Overview

**Task 5: Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.**

This project was completed as part of the **Data Science Internship at Prodigy InfoTech**.

---

## 📂 Dataset

The dataset includes historical records of traffic accidents in the US with the following key features:

- **Start_Time, End_Time**
- **City, State, County**
- **Severity, Weather, Visibility**
- **Temperature, Humidity, Wind, Pressure**
- **Geolocation (Lat, Lng)**

---

## 🔍 Objectives

- Identify the number of accidents based on **severity levels**
- Analyze accidents by **hour, weekday, and month**
- Study impact of **weather conditions**
- Visualize top **cities/states** with high accident counts
- Create **heatmaps, bar charts, pie charts** to identify patterns

---

## 🧪 Key Analysis Performed

- Extracted **hour**, **weekday**, and **month** from accident timestamps
- Grouped data by **State**, **City**, and **Severity**
- Used `groupby()`, `value_counts()`, and `pivot_table` to summarize
- Created **bar plots**, **line plots**, **heatmaps**, and **pie charts** using `matplotlib` and `seaborn`
- Identified **accident-prone time periods** and **weather conditions**

---

## 📊 Visualizations

- 🚗 **Accidents by Severity Level**
- ⏰ **Accidents by Hour of Day**
- 📅 **Accidents by Weekday**
- 🌦️ **Weather Conditions & Accidents**
- 📍 **Top 10 Cities with Highest Accidents**

---

## 🔧 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab

---

## 📌 Conclusion

This project helped in understanding:
- Patterns of accidents across different times and locations
- How to visualize and interpret real-world data for public safety insights

