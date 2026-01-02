# Supplier Operations Performance Dashboard

## 📌 Project Overview
This project presents an **end-to-end Supplier Operations Performance dashboard** built in **Power BI**, focused on monitoring **purchase orders execution, delivery performance, and financial exposure**.

The dashboard provides a clear operational view of:
- How suppliers are performing against purchase orders
- Pending units and pending USD exposure
- Delivery efficiency over time
- Supplier-level operational bottlenecks

![Captura](https://github.com/user-attachments/assets/39367756-7347-4fee-904e-291e1ccf9755)

## 🎯 Business Purpose
The main objectives of this dashboard are:
- Track **Purchase Orders (POs)** and their fulfillment status
- Identify suppliers with **high pending units or USD exposure**
- Monitor **monthly delivery trends**
- Support **data-driven decisions** in procurement and supplier management

---

## 📊 Key Metrics & Visuals
- **Total POs**
- **Total PO Line Items**
- **Total Ordered Units**
- **Total PO Value (USD)**
- **% Units Delivered**
- **% USD Delivered**

- ### Main Visualizations:
- Pending Units by Supplier
- Pending USD by Supplier
- Monthly Units Delivered (time series)
- Detailed transactional table by:
  - Month
  - Supplier
  - Material Document
  - Delivery performance (%)

---

## 🧠 Data Source
- **Original data extracted from SAP** 
- Data was exported to **CSV files** and processed in Power BI
- Supplier names and sensitive identifiers were **anonymized** for confidentiality purposes

---

## 🛠 Tools Used
- **Power BI**
- **DAX**
- **Power Query**
- **SAP (data source)**
- **CSV files**

---

- ## Key Insights

- **Supplier delivery concentration risk**: A small number of suppliers account for the majority of **pending units and pending USD**, increasing operational risk if delivery delays occur.
- **Mismatch between units delivered and financial execution**:The percentage of **USD delivered is lower than the percentage of units delivered**, indicating that higher-value items tend to be delivered later.
- **Uneven delivery performance throughout the year**: Monthly delivery volumes show strong variability, with clear peaks and drops, suggesting opportunities to improve planning accuracy, supplier coordination, and workload leveling across periods.


