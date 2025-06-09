# 🦠 COVID-19 India Dashboard using Power BI

This Power BI project visualizes and analyzes the impact of COVID-19 across Indian states. The dashboard provides interactive insights including total cases, recoveries, death rates, and trends over time, allowing users to monitor the situation effectively.

---

You can view the live Power BI report by clicking the link below:

🔗 [View Live Report on Power BI]([https://app.powerbi.com/view?r=eyJrIjoiMmMyNzFiNTYtMWNlMi00Zjk3LWE1M2QtZjgyOGU3MGQ5YTA3IiwidCI6ImM2NDk4YWJmLWUyOTYtNDkzNy04YzJhLTJmYTlhZDM3YzFjYSJ9](https://app.powerbi.com/view?r=eyJrIjoiMWRjZTc1OWUtZGJlMS00ZDBiLTk0NGYtNTFiYjI2Yzk4ZGQ0IiwidCI6ImM2NDk4YWJmLWUyOTYtNDkzNy04YzJhLTJmYTlhZDM3YzFjYSJ9))

## 📊 Project Summary

- **Tool Used:** Power BI Desktop
- **Data Source:** COVID-19 dataset (state-wise and monthly case data)
- **Mode:** Import Mode
- **Focus:** State-wise & time-based analysis of COVID-19 cases, deaths, and recoveries in India

---

## 🧹 Data Cleaning & Preparation

Performed using **Power Query Editor**:
- Removed duplicates and null values
- Changed data types (date, numeric)
- Renamed columns for clarity
- Created calculated columns (e.g., death rate, recovery rate)
- Extracted month from date column

---

## 🧠 DAX Measures

Created dynamic KPIs using DAX:
- `Total Cases = SUM(cases)`
- `Death Rate = DIVIDE(Total Deaths, Total Cases)`
- `Recovery Rate = DIVIDE(Total Recoveries, Total Cases)`
- Additional calculated columns for month and year

---

## 🧩 Data Modeling

- Defined relationships between tables (if multiple tables were used)
- Ensured proper cardinality and data integrity
- Created lookup tables for filters (e.g., State, Month)

---

## 📈 Visualizations

Built an interactive one-page dashboard with the following elements:

- **KPI Cards:**
  - Total Cases
  - Total Recoveries
  - Death Rate
  - Recovery Rate

- **Pie Chart:**
  - Active Cases vs. Recoveries vs. Deaths

- **Map Visualization:**
  - Active cases by state (bubble size for volume)

- **Bar Chart:**
  - Top 5 states by total cases

- **Line Chart:**
  - Total deaths by month

- **Dropdown Filter:**
  - State selector for detailed filtering

- **Panel for New Deaths:**
  - Displays recently reported fatalities

---

## 🚀 Deployment

- Published to **Power BI Service**
- Configured **Scheduled Data Refresh**
- (Optional) Implemented **Role-Level Security (RLS)**
- Workspace hosted using **Power BI Premium**

---

## 📌 Key Insights

- Delhi recorded the highest number of cases.
- The recovery rate reached 100% based on the dataset.
- Deaths spiked significantly from April onward.
- Active cases made up a small portion of total reported numbers.

---

## 📁 Project Structure

