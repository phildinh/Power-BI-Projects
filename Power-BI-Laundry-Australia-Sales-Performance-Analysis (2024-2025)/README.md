# Laundry Company Sales Performance Analysis (2024–2025)

## Table of Contents
1. Project Overview  
2. Data Model  
3. Client Questions, Business Goals & Analytical Framework  
4. Main Recommendations  
5. Client-Facing Dashboards (Section A)  
6. Executive Summary for Stakeholders (Section A)  
7. Root-Cause Analysis – Sydney Underperformance  
8. Business Question 1: Revenue Volatility Across 2024–2025  
9. Business Question 2: Influential Dimensions of Growth & Contraction  

---

## 1. Project Overview
This project analyzes the sales performance of a national laundry product retailer in Australia across 2024 and 2025. The focus is on understanding trends in revenue, units sold, product demand, and store-level execution. The dataset spans **January 2024 to September 2025**, with granularity across time, product, store, location, and inventory levels. This analysis supports both strategic business evaluation and operational improvements.

---

## 2. Data Model Description
![image](https://github.com/user-attachments/assets/60e4af52-0a06-4aff-8c29-586e6420ce9c)

### 1. Sale Table
- Metrics: `Total_Revenue`, `Total_Profit`, `Total_Cost`, `Units`
- Linked by: `Product_ID`, `Store_ID`, `Date`

### 2. Product Table
- Fields: `Product_ID`, `Product_Name`, `Product_Category`, `Product_Price`, `Product_Cost`

### 3. Store Table
- Fields: `Store_ID`, `Store_Name`, `Store_City`, `Store_Location`, `Store_Open_Date`

### 4. Inventory Table
- Fields: `Product_ID`, `Store_ID`, `Stock_On_Hand`
- Used to calculate **Days of Inventory**

### 5. Date Table
- Fields: `Date`, `Day`, `Month`, `Month_Year`, `Year`

---

## 3. Client Questions, Business Goals & Analytical Framework

### Client’s Key Business Questions:
1. Which city or region is underperforming, and why?  
2. What caused the revenue spike in May 2025 and the dip in March–April?  
3. Which products or categories are consistently underperforming?  
4. Are there inventory risks that could be impacting top-performing products?

### Client’s Business Goals:
- Hit the $38M annual revenue goal for 2025  
- Boost underperforming stores and product categories  
- Maintain inventory health for high-performing SKUs  
- Diagnose and control revenue volatility

### Metrics and Analytical Focus:
- **Key Metrics:** YTD Revenue, YoY Growth Rate, Units Sold, Profit  
- **Supporting Metrics:** MoM Growth, Days of Inventory, Goal Progress  
- **Dimensions:** Store City, Store Location, Product Category, Date  
- **Analysis Types:**  
  - Revenue trend (YoY, MoM)  
  - Performance attribution  
  - Root-cause diagnostics  
  - Inventory efficiency  

---

## 4. Main Recommendations

### 🔍 Strategic Actions:
1. **Revive Sydney**:  
   - Target Coles Store 41 (–3.33%) and IGA Store 4  
   - Refresh stock, push promotions on Soaker/Sanitiser products

2. **Sustain May Momentum**:  
   - Institutionalize campaign planning and stock ramp-up for May-like spikes

3. **Inventory Optimization**:  
   - Replenish low-stock stores like ALDI Store 45 and Woolworths 28 (<0.2 days inventory)

4. **Prevent Q2 Collapse**:  
   - Build seasonal campaigns for Q2  
   - Consider price testing or bundled promos for sensitive categories  

---

## 5. Client-Facing Dashboards (Section A)
- **Dashboard 1**: YTD Revenue vs Goal, YoY by City, Location, Category
![image](https://github.com/user-attachments/assets/460e5e37-b1ec-4c9b-a885-11b6fdc7675e)

- **Dashboard 2**: Product-level growth and volume
![image](https://github.com/user-attachments/assets/da31b0c7-6ee6-4918-9f1a-0fcb8d5c63ed)

- **Dashboard 3**: Store performance and inventory risk  
![image](https://github.com/user-attachments/assets/00bb41bc-ffda-4829-8fab-51bd9fa8877d)

---

## 6. Executive Summary for Stakeholders (Section A)

By September 2025, the company achieved **$28.08M YTD revenue (+1.46% YoY)**, reaching **73.88% of the $38M goal**.  
While growth is positive, it's uneven across cities and categories.

- **Top Contributors**:  
  - City: Darwin (+2.92%), Canberra (+2.08%)  
  - Product Category: Fabric Refresher (+8.58%)

- **Underperformance**:  
  - **Sydney (–0.62% YoY)** is the only major city in decline

- **Inventory Alert**:  
  - High-revenue stores at risk with <1 day of stock for key products

---

## 7. Root-Cause Analysis – Sydney Underperformance
![image](https://github.com/user-attachments/assets/31498095-c3ef-495f-9623-72beb2eaf56b)

- **City YoY Revenue**: –0.62%  
- **By Location**:  
  - CBD: –0.64%, Suburban: –0.54%  
- **By Store**:  
  - Coles Store 41: –3.33%, IGA Store 4: –0.94%  
- **Categories Driving Decline**:  
  - Soaker: –7.84%, Sanitiser: –1.96%, Stain Remover: –4.10%  
- **Worst Products (YoY)**:  
  - Lysol Sanitiser: –9.17%, Preen Remover: –8.76%, PHL Soaker: –7.84%

### ✅ Recommendation:
Reinvest in promotions, adjust product mix, and troubleshoot execution issues in affected stores.

---

## 8. Business Question 1: Revenue Volatility Across 2024–2025

### Root Causes:
- **Q2 2025 Dip (March–April)**:  
  - All locations and cities declined >5% YoY  
  - Categories like Liquid, Soaker, Sanitiser fell 5–7%  
- **May Spike (+25.29%)**:  
  - Bounce-back across all dimensions  
  - Units sold surged +25%, revenue growth driven by Fabric Refresher and Sheets

### ✅ Recommendation:
Plan targeted recovery campaigns before Q2. Forecast seasonal risks earlier using trend data.

📎 *Attach Dashboards 5, 6, 7, 8*

---

## 9. Business Question 2: Influential Dimensions of Growth & Contraction

### Key Dimensions:
- **Product Category**:  
  - Growth: Fabric Refresher, Sheets  
  - Decline: Sanitiser, Soaker  
- **City**:  
  - Growth: Darwin, Adelaide  
  - Decline: Sydney, Melbourne  
- **Store Type**:  
  - Strongest: ALDI, Woolworths  
  - Weakest: Coles  

### ✅ Recommendation:
Expand winning SKUs in high-growth cities. Realign inventory and promotion strategy for declining formats.

📎 *Attach Dashboards 6, 7, 8, 9*

---

## ✅ Final Note

This end-to-end analysis connects executive strategy with root-level diagnostics. All recommendations are evidence-based and tailored for actionable change.  
Next step: embed dashboards and begin execution planning with retail and marketing leads.

