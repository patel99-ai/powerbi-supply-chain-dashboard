# Supply-Chain-Management-Dashboard-Power-BI

## Project Title
**Supply Chain Management Dashboard in Power BI**  

This project provides a comprehensive overview of the supply chain process using a mock dataset. It tracks key KPIs such as revenue, profit margin, stock levels, supplier performance, and logistics costs. The dashboard is designed to help businesses improve efficiency, reduce costs, and make data-driven decisions across procurement, inventory, and distribution functions.

---

## Problem Statement
Supply chains involve multiple stakeholders — suppliers, manufacturers, distributors, and customers. Tracking performance across these stages is challenging because of siloed data, lack of visibility, and difficulties in analyzing key metrics.  

Companies need clear visibility into:
- Revenue by product type, SKU, and customer demographics  
- Supplier quality and defect rates  
- Inventory levels and order quantities  
- Logistics performance and transportation costs  

Without an integrated dashboard, inefficiencies remain hidden and decision-making is delayed.

---

## Flow of the Project
1. **Data Gathering** – Collected supply chain mock data (CSV) including revenue, orders, suppliers, stock levels, and transportation costs.  
2. **Data Cleaning / Transformation** – Removed unnecessary attributes, renamed fields, and standardized formats in Power Query.  
3. **Data Modeling** – Built relationships between fact and dimension tables (e.g., SKU, Supplier, Transportation Mode).  
4. **DAX Functions** – Created measures for KPIs: Total Revenue, Total Cost, Avg Profit Margin %, Stock Level, Order Quantity, Defect Rate %.  
5. **Dashboard Design** – Developed three pages: Overview, Products, Supplies.  
6. **Navigation** – Added interactive filters for SKU and Supplier to drill into insights.  

---

## Project Architecture
- **Data Source**: Mock supply chain dataset (CSV)  
- **ETL**: Power Query (cleaning and transformations)  
- **Data Modeling**: Relationships between SKU, Supplier, and Transport tables  
- **Analytics**: DAX measures for KPIs  
- **Visualization**: Power BI dashboards with interactive charts and KPIs  

---

## Dashboard Pages

### 🔹 Overview Page
- KPIs: Total Revenue, Products Sold, Total Cost, Avg Profit Margin %, Stock Level  
- Revenue breakdown by **Customer Demographics** and **Product Type**  
- Revenue by **Shipping Carriers**  
- Avg Defect Rate % by Product Type  
- Revenue by SKU  
- Supplier Profit Margin %  
<img width="1086" height="597" alt="Screenshot 2025-09-16 193050" src="https://github.com/user-attachments/assets/0ae09c62-6901-4918-b8cd-afd8ce4af235" />

---

### 🔹 Products Page
- KPIs: Revenue, Products Sold, Stock Level, Order Quantity  
- Order Quantity and Stock Levels by SKU  
- Avg Profit Margin % by Product Type  
- Lead Time vs Manufacturing Lead Time (by SKU)  
- Price vs Products Sold scatter plot  
<img width="1059" height="582" alt="Screenshot 2025-09-16 193113" src="https://github.com/user-attachments/assets/8d33d25a-0bfa-4f67-8cb4-5f6953bfa621" />

---

### 🔹 Supplies Page
- Transportation Costs by Mode (Road, Rail, Air, Sea)  
- Avg Defect Rate % by Transport Mode  
- Cost breakdown: Manufacturing + Shipping by Supplier  
- Stock Levels by Supplier  
- Profit Margin vs Defect Rate scatter plot by Supplier  
<img width="1061" height="581" alt="Screenshot 2025-09-16 193119" src="https://github.com/user-attachments/assets/d672c1b2-428c-4fbc-8444-0a6785fd8e50" />

---


---

## ✅ Outcome
- Delivered an **interactive multi-page dashboard** that consolidates supply chain KPIs into one view.  
- Improved **visibility into revenue, inventory, and supplier performance**, making insights easier to act on.  
- Demonstrated how businesses can use Power BI to reduce **manual reporting time** and speed up decision-making.  
- Highlighted inefficiencies in supplier defect rates and transportation costs, supporting **cost reduction strategies**.  
- Created a **portfolio-ready case study** to showcase Power BI, data modeling, and supply chain analytics skills.  

