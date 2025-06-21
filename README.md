# GlobalLogiX---Supply-Chain-Risk-Management
Interactive Power BI Dashboard for Supply Chain Risk Analysis, developed as part of a skill assessment for GlobalLogiX. Includes visualisations, DAX queries, and data insights on supplier risk, shipment delays, stock monitoring, returns, and logistics efficiency.

## 📌 Project Overview

This project was developed as part of a Power BI skill test for GlobalLogiX, a multinational logistics and supply chain company. The objective was to build an interactive, end-to-end dashboard for monitoring supplier risk, shipment delays, inventory shortages, and logistics costs using real-world data scenarios.

## 🎯 Problem Statement

As GlobalLogiX expands its global operations, it faces growing challenges in:

- Identifying unreliable and high-risk suppliers
- Managing delayed and returned shipments
- Monitoring warehouse inventory levels and forecasting stock shortages
- Analyzing operational inefficiencies and freight costs

This dashboard delivers data-driven insights through visual analytics and DAX-powered KPIs to support faster and better decision-making.

## 🧩 Data Sources

The dashboard integrates the following datasets:

- **Suppliers**: Risk scores, reliability ratings, performance data
- **Shipments**: Shipment status, delays, freight costs
- **Orders**: Procurement and delivery timelines
- **Returns**: Return reasons, associated costs
- **Warehouses**: Inventory levels and thresholds

## 🧼 Key Data Transformations

- Created calculated columns and measures using DAX  
- Applied conditional logic to flag delayed shipments and understocked warehouses  
- Built composite risk scoring model using weighted averages  
- Filtered high-risk suppliers dynamically using slicers and custom tables

## 📊 Dashboard Features

- 📈 **High-Risk Supplier Identification**  
- 🚚 **Delayed Shipments Trends (Last 6 Months)**  
- 🏭 **Warehouse Inventory Monitoring with Threshold Flags**  
- 📉 **Return Analysis by Reason**  
- 📦 **On-Time vs Delayed Shipment by Region**  
- 🛠 **Supplier Performance Dashboard (Reliability, Risk, Delivery Time)**  
- 🧮 **Composite Risk Score Model using Weighted KPIs**  
- 💰 **Logistics Cost Breakdown (Freight, Storage, Returns)**

## 📌 DAX Highlights

- `LateShipmentsPct`  
- `Avg Delay Days`, `Avg Freight Cost`, `Avg Risk Score`  
- `Stock Status` flag for warehouse stock health  
- `Composite Risk Score` using supplier, shipment, defect, and shortage data  

## ⚙️ Tools & Technologies

- **Power BI Desktop**  
- **Power Query (ETL)**  
- **DAX (Data Analysis Expressions)**  
- **Relationship Modelling & Dynamic Slicers**  
- **Custom Measures and Conditional Formatting**

## 🧠 Key Takeaways

- Demonstrated ability to work with complex relational data
- Delivered actionable insights through real-time KPIs and scenario-based design
- Applied best practices in data modeling, transformation, and dashboard storytelling
