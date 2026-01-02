# Supplier Operations Performance Dashboard

## 📌 Project Overview
This project presents an **end-to-end Supplier Operations Performance dashboard** built in **Power BI**, focused on monitoring **purchase order execution, delivery performance, and financial exposure**.

The dashboard provides a clear operational view of:
- Supplier performance against purchase orders  
- Pending units and pending USD exposure  
- Delivery efficiency over time  
- Supplier-level operational bottlenecks  

![Captura](https://github.com/user-attachments/assets/c1af4c48-e043-43d1-bb9e-0743b0f49a76)

---

## 🎯 Business Purpose
The main objectives of this dashboard are to:
- Track **Purchase Orders (POs)** and their fulfillment status  
- Identify suppliers with **high pending units or USD exposure**  
- Monitor **monthly delivery trends**  
- Support **data-driven decisions** in procurement and supplier management  

---

## 📊 Key Metrics & Visuals

### KPIs
- Total POs  
- Total PO Line Items  
- Total Ordered Units  
- Total PO Value (USD)  
- % Units Delivered  
- % USD Delivered  

### Main Visualizations
- Pending Units by Supplier  
- Pending USD by Supplier  
- Monthly Units Delivered (time series)  
- Transaction-level detail including:
  - Month  
  - Supplier  
  - Material Document  
  - Delivery performance (%)  

---

## 🧠 Data Source
- Original data extracted from **SAP**
- Data exported to **CSV files** and transformed in Power BI  
- Supplier names and sensitive identifiers were **anonymized** for confidentiality purposes  

---

## 🛠 Tools Used
- **Power BI**
- **DAX**
- **Power Query**
- **SAP (data source)**
- **CSV files**

---

## 🔍 Key Insights

- **Supplier delivery concentration risk**: A small number of suppliers account for the majority of **pending units and pending USD**, increasing operational risk if delivery delays occur.
- **Mismatch between physical and financial execution**: The percentage of **USD delivered is lower than the percentage of units delivered**, indicating that higher-value items tend to be delivered later, increasing short-term financial exposure.
- **Uneven delivery performance throughout the year**: Monthly delivery volumes show strong variability, with clear peaks and drops, highlighting opportunities to improve planning accuracy, supplier coordination, and workload leveling.

---

## 📁 Repository Structure & Files Description

This repository contains the following files used to build and document the dashboard:

- **Supplier Operations Performance Dashboard.pbix**: Interactive **Power BI report file**
- **Supplier Operations Performance Dashboard_2025.pdf**: Static **snapshot of the dashboard for year 2025**, exported from Power BI.
- **ME2N.xlsx**: SAP export related to **Purchase Orders**.
- **MB51.xlsx**: SAP export related to **Goods Movements**
- **Suppliers.xlsx**: Supplier master data and normalization

---


