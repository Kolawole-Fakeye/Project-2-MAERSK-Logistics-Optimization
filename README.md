# 🚢 Maersk Logistics: Route Efficiency Optimization
**Project Lead:** Kolawole Fakeye  
**Domain:** Supply Chain / Data Engineering / Logistics  

## 📌 Project Overview
This project analyzes maritime logistics data to identify fuel inefficiencies across West African trade routes. By calculating **Fuel Consumption per TEU**, the system flags specific voyages and ports that are operating above the expected cost-baseline.

## 🛠️ Technical Stack
- **Language:** R (Tidyverse)
- **Methodology:** Data aggregation and fuel-to-cargo ratio analysis.
- **KPIs:** Liters per TEU (Twenty-foot Equivalent Unit) and Port Delay impact.

## 📊 Comparison: Lagos vs. Abidjan
The analysis revealed a significant variance in operational efficiency:
* **Abidjan:** Higher efficiency due to lower port delay hours.
* **Lagos:** Identified as a "High-Friction" zone where ships burn more fuel per container due to idling and congestion.

## 📂 Repository Contents
- `logistics_optimization.R`: The transformation logic and aggregation script.
- `maersk_logistics_efficiency.csv`: The processed data with efficiency metrics.
- `Maersk_Efficiency_Report.png`: Visualization of fuel waste across ports.
