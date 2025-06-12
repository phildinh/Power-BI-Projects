# Laundry Company Sales Performance Analysis (2024–2025)

## Table of Contents
1. Project Overview  
2. Data Model  
3. Client Questions, Business Goals & Analytical Framework  
4. Main Recommendations  
5. Client-Facing Dashboards (Section A)  
6. Executive Summary for Stakeholders (Section A)  
7. Root-Cause Analysis – Sydney Underperformance  
8. Deep-Dive Dashboard Exploration (Section B Overview)  
9. Business Question 1: Revenue Volatility Across 2024–2025  
10. Business Question 2: Influential Dimensions of Growth & Contraction  


---

## 1. Project Overview
This project analyzes the sales performance **(One million sales transactions)** of a national laundry product retailer in Australia across 2024 and 2025. The focus is on understanding trends in revenue, units sold, product demand, and store-level execution. The dataset spans **January 2024 to September 2025**, with granularity across time, product, store, location, and inventory levels. This analysis supports both strategic business evaluation and operational improvements.

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

Despite national revenue growing +1.46% YoY, Sydney recorded a **–0.62% YoY revenue decline**, making it the only major city in negative territory. The decline is not isolated, but structural — spread across locations, stores, and product categories.

### 📍 Location-Level Analysis
- **CBD**: –0.64% revenue, –0.24% units sold  
- **Suburban**: –0.54% revenue, –0.66% units sold  
→ Declines are consistent across both store location types, indicating market-wide weakness in Sydney.

### 🏪 Store-Level Analysis
- **Coles Store 41**: –3.33% revenue, –2.66% units  
- **IGA Store 4**: –0.94% revenue, –0.12% units  
- Two Woolworths stores also declined slightly (–0.20% to –0.54%)  
- Only one Woolworths location posted positive growth: **+2.00% revenue, +2.66% units**  
→ Coles Store 41 is the single largest contributor to the city’s underperformance.

### 🧺 Category-Level Performance in Sydney
- **Underperformers in Units Sold**:  
  - **Laundry Soaker**: –7.84%  
  - **Stain Remover**: –4.10%  
  - **Sanitiser**: –1.96%  
→ These categories show both sharp demand drops and weak price recovery.

### 🧾 Product-Level Impact (Top Declining SKUs in Sydney)
| Product Name                                  | YoY Revenue Decline |
|----------------------------------------------|----------------------|
| Lysol Laundry Sanitizer Free & Clear         | –9.17%               |
| Preen Oxi Action Stain Remover Gel           | –8.76%               |
| PHL Di-San Laundry Soaker                    | –7.84%               |
| Napisan Vanish Gold Pro Stain Remover        | –7.72%               |
| Cold Power Advanced Clean Laundry Liquid     | –5.92%               |

These SKUs dominate the negative side of Sydney’s product performance, particularly in Soaker and Sanitiser categories.

---

### ✅ Recommendation:
1. **Coles-Focused Action Plan**: Launch targeted recovery initiatives at Coles Store 41 (pricing promos, assortment reset).
2. **Re-engage Failing Categories**: Audit Soaker/Sanitiser strategy in Sydney; test in-store activations or promo bundling.
3. **Woolworths as a Bright Spot**: Replicate winning tactics from the Woolworths store showing +2% YoY growth.
4. **Product Rationalization**: Consider rationalizing or repositioning persistent low-performers like Lysol Sanitiser in Sydney if trends continue.

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

Dashboard 5 reveals the clearest view of revenue volatility across 2024–2025 through MoM and YoY trend lines. The data shows two standout movements:  
- A sharp **revenue and unit decline in March–April 2025**  
- A significant **recovery in May 2025**

---

### 📉 March–April 2025 Decline (Dashboard 5)
- **MoM Revenue Drop**:  
  - March: –11.06%  
  - April: –1.01%  
- **MoM Units Sold**:  
  - March: –11.03%  
  - April: –0.64%  
→ These drops represent the lowest two-month performance stretch in the observed timeframe.

### 🔍 Root-Cause Breakdown:
**Across Locations (Dashboard 6):**  
- Suburban: –6.25% YoY revenue (Apr)  
- CBD: –6.58%  
- Commercial & Residential: ~–5%  

**Across Cities (Dashboard 7):**  
- Sydney: –7.82%  
- Melbourne: –7.25%  
- Canberra: –5.57%  
→ City-level declines were synchronized, pointing to a macro-level disruption (e.g., consumer behavior shift, supply challenge, post-promo drop).

**Across Categories (Dashboard 8/9):**  
- Laundry Sanitiser: –7.18% (Apr)  
- Laundry Liquid: –5.81%  
- Stain Remover & Soaker: > –5.5%  
→ The decline was demand-driven, affecting volume-heavy and hygiene-focused categories.

---

### 📈 Recovery in May 2025
- **MoM Revenue Jump**: +25.29%  
- **MoM Units Sold**: +25.06%  
- **City & Location Rebound**: All major cities and store types shifted back to positive YoY  
- **Category Leaders**:  
  - Fabric Refresher: +4.42%  
  - Laundry Liquid: +2.26%  
  - Sheets: +1.93%

---

### ✅ Recommendation:
- **Operational Planning**: Pre-stock and price optimize key SKUs before March. Develop seasonal protection plans for Q2.
- **Trend-Based Promotions**: Use early-March signals (e.g., unit softness) as promo triggers.
- **Marketing Sync**: Amplify cross-category campaigns in May to sustain surge across more cities and store types.

📎 *Attach Dashboards 5, 6, 7, 8*

---

## 10. Business Question 2: Which dimensions most influenced growth and contraction?

This question uncovers the structural levers behind volatility — from product lines to city performance and retail chain behavior.

### 🧺 Product Category Influence (Dashboard 8/9)
- **Growth Drivers** (Jun–Sep):  
  - Fabric Refresher: +8.58% YoY  
  - Laundry Sheets: strong rebound (+6.09% in Sydney alone)  
- **Declining Categories (Mar–Apr)**:  
  - Sanitiser, Soaker, Stain Remover: all declined 5–7% YoY consistently

### 🏙️ City-Level Impact (Dashboard 7)
- **Growth Cities**:  
  - Darwin: +2.92%  
  - Adelaide & Canberra: steady mid-single-digit growth  
- **Lagging Cities**:  
  - Sydney: –0.62% YoY  
  - Melbourne: <+1% with volatility  
→ Geography was a key segmentation lever in both positive and negative periods.

### 📍 Store Location (Dashboard 6)
- Residential and Commercial stores recovered faster and showed less contraction than CBD/Suburban formats.

### 🛒 Retail Channel Performance
- **Winners**: Woolworths and ALDI led growth in both revenue and inventory turnover  
- **Laggards**: Coles stores showed poor YoY revenue, stock gaps, and greater unit decline risk

---

### ✅ Recommendation:
- **Double Down on Growth Areas**: Focus more SKUs and campaigns in Darwin, Adelaide, Residential zones, and Woolworths channels.
- **Corrective Strategy for Coles**: Test price, space allocation, and promotion bundle adjustments.
- **Flexible Inventory Allocation**: Let category performance guide store-level inventory thresholds month-to-month.

📎 *Attach Dashboards 6, 7, 8, 9*

---

## ✅ Final Note

This end-to-end analysis connects executive strategy with root-level diagnostics. All recommendations are evidence-based and tailored for actionable change.  
Next step: embed dashboards and begin execution planning with retail and marketing leads.

