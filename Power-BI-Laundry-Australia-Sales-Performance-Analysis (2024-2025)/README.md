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
- **Dashboard 4**: Root-cause breakdown for Sydney  
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

## 8. Deep-Dive Dashboard Exploration (Section B Overview)

Section B consists of five dashboards designed for root-cause and time-series exploration. These provide deeper insight into what’s driving volatility and product/category shifts.

- **Dashboard 5**: Overall revenue and unit trend (MoM, 2024–2025)
![image](https://github.com/user-attachments/assets/31e913f8-1cc3-46c4-b9b1-de5567b52b06)

- **Dashboard 6**: Location-based monthly share and YoY performance
![image](https://github.com/user-attachments/assets/d0af25c0-71fa-4b5e-95c8-16765c74b5c3)

- **Dashboard 7**: City-based monthly share and YoY performance
![image](https://github.com/user-attachments/assets/f5f7c8b3-ba0b-48cf-8986-71b80e0a5dc7)

- **Dashboard 8/9**: Category-level trend, volume share, and YoY comparisons
![image](https://github.com/user-attachments/assets/1cf59ab9-bdb8-47be-9f37-5b4fce29abdc)


These dashboards create a layered view — starting with the macro revenue curve, then slicing by location, city, and product category to explain specific shifts.

---

## 9. Business Question 1: What explains the revenue volatility across 2024–2025?

Dashboard 5 highlights a major **revenue dip in March–April** and a **sharp rebound in May 2025**. To explain:

### 📉 March–April Declines:
- Revenue fell across **all store locations** (Dashboard 6):  
  - CBD: –6.58%  
  - Commercial: –6.05%  
  - Residential: –5.61%
- Simultaneous declines in **major cities** (Dashboard 7):  
  - Sydney: –7.82%  
  - Melbourne: –7.25%  
  - Adelaide: –6.00%
- **Product category YoY drops** (Dashboard 8):  
  - Laundry Liquid: –5.81%  
  - Soaker: –5.67%  
  - Sanitiser: –7.18%

### 📈 May Rebound Drivers:
- Revenue and units sold rebounded sharply:  
  - +25.29% MoM revenue  
  - +25.06% MoM units sold
- Volume-driven recovery seen across **Fabric Refresher**, **Sheets**, and **Softener**  
- Every city and location saw neutral or positive YoY growth in May

### ✅ Recommendation:
Develop early-warning alerts based on seasonal trend patterns and past volatility. Design a Q2-specific promotional playbook, launching campaigns and adjusting inventory by late Q1 to protect against multi-dimensional slowdowns. Sustain May’s momentum by mirroring stock and pricing strategies.

---

## 10. Business Question 2: Which dimensions most influenced growth and contraction?

Several dimensions contributed directly to both revenue growth and contraction across the reporting period.

### 📊 Key Contributors & Drivers:

- **Product Categories (Dashboard 8/9):**  
  - **Growth**: Fabric Refresher, Laundry Sheets (esp. July–Sep)  
  - **Decline**: Sanitiser, Soaker, Stain Remover (notable dip Mar–Apr)

- **Cities (Dashboard 7):**  
  - **Growth Drivers**: Darwin, Adelaide, Perth  
  - **Contraction**: Sydney and Melbourne

- **Locations (Dashboard 6):**  
  - Commercial and Residential zones showed higher resilience and positive growth  
  - CBD and Suburban lagged behind across multiple months

- **Retail Chains / Store Level:**  
  - **Positive**: Woolworths and ALDI stores outperformed in both revenue and inventory efficiency  
  - **Negative**: Coles branches showed multiple cases of negative growth and stockouts

### ✅ Recommendation:
Prioritize resources (marketing, inventory, store training) in proven growth areas like Fabric Refresher, Residential/Commercial locations, and outperforming cities. For Coles and Sydney/Melbourne, design pilot programs for localized campaigns, optimized pricing, and replenishment logic. Monitor MoM metrics closely to catch shifts early.

---

## ✅ Final Note

This end-to-end analysis connects executive strategy with root-level diagnostics. All recommendations are evidence-based and tailored for actionable change.  
Next step: embed dashboards and begin execution planning with retail and marketing leads.

