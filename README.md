# Supplier Operations Performance Dashboard

This repository contains two Power BI dashboards that provide a comprehensive view of supplier operations and performance, designed to support procurement, supply chain, and supplier management teams in data-driven decision-making.

---

## 📌 Dashboard 1 – Supplier Operations Performance

<img width="1071" height="611" alt="image" src="https://github.com/user-attachments/assets/4eb8b2b2-c69c-4c82-8e83-1a5667dd0561" />

### Overview
An end-to-end dashboard focused on monitoring purchase order execution, delivery performance, and financial exposure.

### Business Purpose
- Track Purchase Orders (POs) and their fulfillment status  
- Identify suppliers with high pending units or USD exposure  
- Monitor monthly delivery trends  
- Support data-driven decisions in procurement and supplier management  

### Key Metrics & Visuals
**KPIs:** Total POs, Total PO Line Items, Total Ordered Units, Total PO Value (USD), % Units Delivered, % USD Delivered  

**Visualizations:**  
- Pending Units by Supplier  
- Pending USD by Supplier  
- Monthly Units Delivered (time series)  
- Transaction-level details: Month, Supplier, Material, Document, Delivery Performance (%)  

### Data Source & Tools
- SAP exports (ME2N, MB51) and CSV files, transformed in Power BI  
- Supplier identifiers anonymized  
- Power BI, DAX, Power Query  

### Insights
- High concentration risk: few suppliers account for most pending units and USD  
- Delays in high-value items increase short-term financial exposure  
- Monthly delivery volumes show strong variability, highlighting planning and coordination opportunities  

---

## 📌 Dashboard 2 – Supplier Performance

<img width="1070" height="609" alt="image" src="https://github.com/user-attachments/assets/5c7fe654-f88f-40d8-98bc-37b615ed1f42" />

### Overview
A dashboard focused on supplier delivery efficiency, lead time, and units delivered compared to historical averages.

### Business Purpose
- Monitor suppliers’ delivery performance against historical benchmarks  
- Identify suppliers with unusually high lead times or exceptional delivery volumes  
- Analyze trends in lead time and units delivered over time  
- Support operational improvements and workload planning  

### Key Metrics & Visuals
**KPIs:** Lead Time (Days) vs Historical Average, Average Units Delivered vs Historical Average  

**Visualizations:**  
- Average Lead Time by Year (time series with historical reference)  
- Units Delivered by Year (time series with historical comparison)  
- Supplier-Level Lead Time (horizontal bar chart)  
- Supplier-Level Units Delivered (horizontal bar chart)  

### Data Source & Tools
- SAP and internal ERP exports to CSV, transformed in Power BI  
- Supplier identifiers anonymized  
- Power BI, DAX, Power Query  

### Insights
- Some suppliers exceed historical lead time averages, indicating potential bottlenecks  
- Few suppliers deliver most units, posing operational risk if delays occur  
- Variability in lead time and delivered units highlights opportunities for optimization  

---

## 📁 Files in Repository
- `Supplier Operations Performance Dashboard.pbix`  
- `Supplier Operations Performance Dashboard.pdf`  
- `ME2N.xlsx`  
- `MB51.xlsx`  
- `Suppliers.xlsx`  
