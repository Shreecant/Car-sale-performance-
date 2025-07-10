# 🚗 Car Sales Data Analysis & Power BI Dashboard

This project showcases a complete **end-to-end data analysis workflow** using Python and Power BI. The goal was to analyze car sales performance, uncover trends by brand and model, and build an interactive dashboard that turns raw data into insights.

---

## 📌 Project Overview

- 🔍 **Objective:** Analyze car sales data to find high-performing manufacturers, models, and revenue trends.
- 🔧 **Process:** Data was cleaned and transformed in Python (Google Colab) and visualized in Power BI.
- 📊 **Output:** A professional dashboard showing sales, revenue, and trends.

---

## 🧰 Tools Used

- **Python (Pandas)** – For data cleaning & transformation
- **Google Colab** – Interactive Python environment
- **Power BI** – For creating dynamic and interactive visuals
- **CSV Dataset** – `Car_sales.csv` (included in repo)

---

## 🔄 Workflow

### 1. Data Collection
Raw dataset `Car_sales.csv` contains:
- Car model, brand, vehicle type
- Sales volume and price
- Launch date and resale value

### 2. Data Cleaning (Python)
Key steps:
- Renamed messy column headers
- Converted dates (`Latest_Launch`) into datetime
- Handled missing values using `.fillna()`
- Created a new metric:  
  ```python
  Revenue_in_millions = Sales_in_thousands * Price_in_thousands / 1000
