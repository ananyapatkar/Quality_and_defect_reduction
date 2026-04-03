# Quality_and_defect_reduction


## 🚀 Overview
This project presents an end-to-end quality analytics solution for a manufacturing environment. It leverages Excel, SQL, Python, and Power BI to monitor defect trends, identify anomalies, analyze machine performance, and perform root-cause analysis using sensor data.

---

## 🎯 Objectives
- Monitor daily defect trends across plants  
- Detect abnormal spikes using statistical thresholds  
- Identify underperforming machines  
- Analyze root causes using operational data  
- Build predictive and clustering models for quality improvement  

---

## 🛠️ Tools & Technologies
- **Excel** – Pivot Tables, Rolling Average, Conditional Formatting  
- **SQL** – Aggregations, Window Functions, Views  
- **Python** – Regression, Clustering (Scikit-learn)  
- **Power BI** – Interactive dashboards, visual analytics  

---

## 📊 Excel Analysis

### 🔹 Defect Performance Report
- Created **DefectRate = DefectCount / ProductionUnits**
- Built plant-wise and machine-wise pivot analysis  
- Identified **Top 15 machines by average DefectRate**
- Daily DefectCount trend per plant  
- 7-day rolling average

  
---

## 🗄️ SQL Analysis

### 🔹 Daily Metrics
- Computed:
  - Daily DefectCount per plant  
  - Daily DefectRate per plant  
  - Rolling 7-day average using window functions  

---

### 🔹 Quality Hotspots View
- Created view: `quality_hotspots_2025`
- Identified machines in **top 10% DefectRate within each plant**
- Included:
  - Avg Temperature  
  - Avg Vibration  
  - Avg Pressure  

---

## 🐍 Python Analysis

### 🔹 Regression Model
- Predicted DefectRate using:
  - Vibration, Temperature, Pressure  
  - EnergyConsumption, ProductionUnits  
- Evaluated feature importance  

---

### 🔹 Clustering Analysis
- Clustered machines based on:
  - DefectRate  
  - Vibration  
  - Temperature  
  - Pressure  

- Labeled clusters such as:
  - High Defect / High Vibration  
  - Stable Machines  
  - Process-driven defects  

---

## 📊 Power BI Dashboard

### 🔹 Quality Dashboard
- DefectRate by Plant  
- Top defect machines  
- Daily defect trend  
- Interactive slicers (Plant, Machine)

---

### 🔹 Root Cause Analysis
- Scatter Plot:
  - X-axis → Vibration  
  - Y-axis → DefectRate  
  - Size → ProductionUnits  
  - Color → Plant  

- Tooltip includes:
  - Temperature  
  - Pressure  

---

## 📈 Key Insights
- Higher vibration is associated with increased defect rates  
- A small set of machines contributes disproportionately to defects  
- Statistical thresholds effectively identify anomaly days  
- Clustering reveals distinct machine behavior patterns  

---

## 🚀 How to Use
1. Open Excel files for monitoring and analysis  
2. Run SQL scripts for data processing  
3. Execute Python notebooks for modeling  
4. Open Power BI report for interactive insights  

---
