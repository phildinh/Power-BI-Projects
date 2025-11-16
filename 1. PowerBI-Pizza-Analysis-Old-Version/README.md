# 🍕 Pizza Sales Analytics Dashboard

## 📌 Overview  
The **Pizza Sales Analytics Dashboard** was developed to uncover actionable insights across four key business areas: sales trends, operational performance, product popularity, and price sensitivity. Built with **Power BI**, this report supports data-driven decisions around marketing, pricing strategy, staffing optimization, and inventory management.

Through interactive visualizations, this dashboard allows business owners and managers to quickly identify which products perform best, when their stores are busiest, and how pricing and size affect revenue.

---

## 🎯 Purpose  
This dashboard was built in response to business questions from stakeholders, including:

- How do sales fluctuate over time?
- When are the busiest and slowest periods for operations?
- Which pizzas, categories, and sizes generate the most revenue?
- How can pricing strategies be optimized to increase profit?

---

## 🧩 Dataset & Model  
This project uses a **snowflake schema** consisting of:

- `Fact_Order`: sales transactions, revenue, size, and time  
- `Dim_Pizza`: pizza name, category, size, price  
- `Dim_Date`: date-level attributes (month, quarter, weekday, etc.)  
- `Dim_Time`: hour-level time tracking for peak-hour analysis  

---

## 🛠️ Tools Used  
- **Power BI**: Main dashboard development and DAX measures  
- **Power Query**: Data shaping, cleaning, schema building  
- **Excel**: Data auditing, validation  
- **DAX**: Used to calculate KPIs like average order value, heatmaps, and price elasticity indicators  

---

## 📊 Dashboard Visuals  
![image](https://github.com/user-attachments/assets/48dcb581-38ac-45f3-9018-0a164fd9098f)
![image](https://github.com/user-attachments/assets/6f4e951c-8b1f-4fdb-b5a0-b10985963fd6)
![image](https://github.com/user-attachments/assets/0117afc8-4c02-4516-bf6a-71ad2d9abf0e)




---

## 📌 Key Dashboard Sections  

### 1. 📈 **Sales Trend Analysis**  
![image](https://github.com/user-attachments/assets/5daf900a-2197-4b5e-9b36-b98be5e8a979)

- **Total Orders**: 21,350 | **Total Revenue**: $817,860  
- Highest monthly orders occurred in **July**, while **Quarter 3** had the highest order volume  
- However, **Quarter 2** yielded the **highest revenue**, indicating pricing/size differences  
- November showed higher revenue despite fewer orders, due to larger pizza sizes and seasonal boosts (Black Friday, Thanksgiving)

> 📌 **Recommendation**: Focus on increasing average order value through upselling sides or drinks, and promoting high-margin large and extra-large pizzas.

---

### 2. ⏱️ **Working Hour & Day Performance**  
![image](https://github.com/user-attachments/assets/7e2529c6-a6ab-4b0e-b493-9ab05c12e862)

- **Friday** leads in both **order volume** and **revenue**  
- **Peak hours**:  
  - **Lunch rush**: 12 PM–1 PM  
  - **Dinner surge**: 5 PM–7 PM  
- **Evening orders** spike on **Fridays & Saturdays** between **8 PM–10 PM**  
- Very low revenue hours: **9–10 AM** and post **10 PM**

> 📌 **Recommendations**:  
- Optimize staff scheduling during Friday/Saturday peak hours  
- Consider adjusting business hours to **11 AM–10 PM**  
- Cross-train staff to improve flexibility during high-demand hours

---

### 3. 🍕 **Product Performance**  
![image](https://github.com/user-attachments/assets/d3696ce0-b520-40ac-a671-1269767b9e1d)

- **Most ordered pizza**: *The Classic Deluxe Pizza*  
- **Highest revenue pizza**: *The Thai Chicken Pizza*  
- **Least performance (order + revenue)**: *The Brie Carre Pizza*  
- **Top category by orders**: Classic  
- **Top category by revenue %**: Chicken (27.27%), followed closely by Veggie and Supreme  
- **Large-sized pizzas** dominate revenue (45.89%) despite not being the most ordered

> 📌 **Insights**:  
- Focus inventory and marketing efforts around top sellers (Classic & Chicken categories)  
- Consider phasing out low performers or repackaging them with promos

---

### 4. 💰 **Price Sensitivity & Size Strategy**  
![image](https://github.com/user-attachments/assets/10f374a0-0f69-4caf-bc36-dee9fcaaa48d)

- **Large (L)** and **Medium (M)** sizes generate most of the revenue  
- **XL pizzas** have highest average revenue per unit ($25.50) but low order volume  
- **Brie Carre Pizza** (small size only) has low order count but above-average revenue per sale

> 📌 **Recommendations**:  
- **Increase** prices of Classic category’s small and medium sizes  
- **Raise** the price of **large Veggie pizzas** to match value perception  
- **Lower** price of large Supreme pizzas slightly to stimulate sales  
- **Promote** Brie Carre Pizza via bundling deals (e.g., "Buy 1 Brie Carre, get 30–50% off any Classic small pizza")

---

## ✅ Summary of Recommendations  

- 🛒 **Boost AOV**: Upsell drinks/sides and promote combo deals  
- 🔥 **Capitalize on hot hours**: Staff up 12 PM–1 PM & 5 PM–7 PM, Fri–Sat  
- 🧾 **Product mix shift**: Focus on high-margin SKUs (XL & L), phase out low performers  
- 💸 **Adjust pricing**: Based on size, demand elasticity, and average revenue per pizza  
- 📦 **Bundle promotions**: Incentivize purchase of underperforming but profitable SKUs  

---

## 📄 License  
Specify the license under which the project is released.

---

## 📬 Contact  
For more information or collaboration:  
**Phil Dinh**  
📧 [phildinhdata@gmail.com](mailto:phildinhdata@gmail.com)
