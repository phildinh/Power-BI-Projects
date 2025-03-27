# 🛡️ Insurance Analytics Dashboard  

## 📌 Overview  
The **Insurance Analytics Dashboard** provides a comprehensive view into the performance of insurance and wealth products across various business lines, regions, and advisor segments. Built using **Power BI**, this dashboard enables business leaders to uncover sales trends, assess advisor performance, and make strategic decisions based on data-driven insights.

It combines sales, withdrawals, and net sales in one centralized platform while offering drill-downs by region, product, contract type, and customer risk level. The result is a tool that transforms complex data into clear and actionable intelligence.

---

## 🎯 Purpose  
This dashboard was created in response to a need for better visibility into the performance of multiple insurance products and financial offerings. It addresses the following business goals:

- Understand year-over-year trends for sales and withdrawals  
- Identify underperforming vs. high-performing products and advisors  
- Evaluate risk levels and customer preferences by product type  
- Support executive-level decision-making with visual performance insights

---

## 🧩 Dataset  
The underlying dataset combines multiple sources, including transactional sales records, advisor performance metrics, and customer segmentation data.

- **Fact Table**: Transactional sales data (with risk levels, product categories, time, region, and amount)  
- **Dimension Tables**:  
  - `Advisor_Dim`: advisor-level data and YoY performance  
  - `Product_Dim`: insurance and wealth product metadata  
  - `Date_Dim`: full calendar-based time intelligence  
  - `Region_Dim`: geo-mapped sales region info  

The data model is built using a star schema, supporting fast and flexible filtering across visuals.

---

## 🛠️ Tools Used  
- **Power BI**: For building interactive dashboards and visual storytelling  
- **Power Query**: For preparing, transforming, and cleaning source datasets  
- **DAX**: Used for KPIs, YoY comparisons, performance metrics, and calculated segments  
- **Microsoft Excel**: For initial data validation and manual reconciliation  

---

## Dashboards
![image](https://github.com/user-attachments/assets/a092bef7-e0b0-4e7f-b86c-3b163af8a4c1)


## Dashboard breakdowns
![image](https://github.com/user-attachments/assets/71e3b1ae-cb46-44e2-862b-b8aae1c3702a)
![image](https://github.com/user-attachments/assets/b57f0e8d-117d-4667-89c4-108616976618)
![image](https://github.com/user-attachments/assets/3b4f4e04-c830-47ba-87f4-521b332eba93)

---

## 📌 Key Dashboard Sections  

### 1. **📈 Executive Summary**  
- **CY Sales**: $407K, down 9% YoY  
- **CY Withdrawals**: $103K, up 157% YoY  
- **Net Sales**: $304K, down 25% YoY  
- Top business line: **Life Insurance** ($197K)  
- Insights into performance by **product**, **region**, and **risk level**  

---

### 2. **💰 Wealth Page**  
- **Mutual Fund Sales**: $19K (+109% YoY)  
- **Retirement Savings**: $24K (+168% YoY)  
- **Stock Portfolio Sales**: $6.8K (−57% YoY)  
- Region-level analysis and contract type breakdown  
- Advisor-level contribution analysis  

> Key Insight: Wealth products are gaining traction, particularly among customers planning for retirement or seeking long-term investment options.

---

### 3. **🏠 Insurance Page**  
- **Car & Home Insurance**: Mixed performance  
  - Strong growth in **Comprehensive Cover** (+417%)  
  - Steep decline in **Flood Cover** (−85%) and **Third-Party Fire & Theft** (−73%)  
- **Life Insurance**:  
  - **Universal Life** up by 12%  
  - **Whole Life** down by 45%  
- Risk Level Breakdown: Customers lean toward **low-to-moderate risk** products  
- Performance tracked month-by-month and by individual advisor  

---

### 4. **🧑‍💼 Advisor Performance**  
- High performers:  
  - **Charles Morris** (+139% YoY)  
  - **Sharon Johnson** (+191% YoY)  
- Underperformers:  
  - **Jennifer Harmon** (−87% YoY)  
- Insights reveal training gaps, portfolio allocation issues, or differing market conditions

> Opportunity: Leverage high-performers’ strategies across teams and implement support programs for advisors with declining results.

---

## ✅ Recommendations  

- **Wealth Focus**: Continue expanding retirement savings and mutual fund offerings; capitalize on growing demand through product bundles and investor education.  
- **Insurance Optimization**:  
  - Reevaluate product pricing and competitiveness for declining areas (e.g., Flood Cover).  
  - Explore marketing strategies for rising categories like Comprehensive Car Coverage and Universal Life.  
- **Advisor Enablement**:  
  - Launch skill-development programs for underperformers.  
  - Align compensation or incentives to drive key product sales.  
- **Data-Driven Planning**:  
  - Use this dashboard for monthly review sessions, real-time strategy shifts, and identifying advisor training needs.  
- **Regional Strategies**:  
  - Tailor offerings and communication by state and risk preferences.  
  - Use map visualizations to spot untapped or underperforming regions for future campaigns.

---

## 📄 License  
Specify the license under which the project is released.

---

## 📬 Contact  
For more information or collaboration:  
**Phil Dinh**  
📧 [phildinhdata@gmail.com](mailto:phildinhdata@gmail.com)

