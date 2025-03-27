# ☕ Penguin Coffee Sales Dashboard – 2023 Half-Time Review  

## 📌 Overview  
The **Penguin Coffee Sales Dashboard** provides an in-depth mid-year performance review for Penguin Coffee’s **Sydney Sales Region**, covering data from three flagship stores: **Newtown, Bankstown, and North Sydney**. Developed in Power BI, this interactive report enables stakeholders to track performance metrics, explore customer behavior, optimize store operations, and forecast full-year revenue based on current trends.

Built for business leaders and operations teams, the dashboard tells a cohesive story—from overall KPIs to granular performance by product, category, store location, and time of day.

---

## 🎯 Purpose  
As Penguin Coffee continues expanding across Sydney, leadership needed a comprehensive analytics dashboard to answer critical business questions:

- What are our **core performance metrics** so far in 2023?
- Which **product categories and items** are driving revenue?
- Which **time of day** generates the most sales?
- How can we **streamline store operations**?
- What are our **sales projections** for the rest of the year?

This dashboard serves as a **central decision-making tool** to guide promotional strategy, staffing schedules, and inventory planning.

---

## 🧩 Dataset  
The dataset used for this project consists of over **149,000 transaction records** across 3 physical store locations in Sydney. Key data includes:

- **Sales transactions**: Quantity, time, order value, store
- **Product details**: Category, item type
- **Customer behavior**: Purchase timing patterns
- **Store info**: Location-based performance

The data model follows a **star schema** with clearly defined dimensions and fact tables:
- `Product_Dim`
- `Store_Dim`
- `Date_Dim`
- `Forecast Date Table`
- `Penguin_Koffee_Fact` (central fact table)

---

## 🛠️ Tools Used  
- **Power BI**: For data modeling, DAX calculations, and building interactive visuals  
- **Power Query**: For cleaning and transforming raw data  
- **DAX**: For calculating KPIs, forecasting logic, and time intelligence  
- **Forecasting Techniques**: Leveraged built-in Power BI forecasting models to project full-year revenue  

---

## 📊 Dashboards  
![image](https://github.com/user-attachments/assets/7443e3dc-663f-4c55-9e03-d08cfd5a172b)
![image](https://github.com/user-attachments/assets/10b08570-ef2f-4f3c-92ea-a91995ce9c9f)
![image](https://github.com/user-attachments/assets/b624fbb5-9ce6-4e3f-8db5-9ec9cc4376df)


---

## 📌 Key Dashboard Sections  

### 1. **💡 Executive Summary (Top Cards)**  
- Total Sales: **$698,812**  
- Transactions: **149,116**  
- Avg. Order Size: **$4.69**  
- Best-selling item: *Crow’s Nest Croissant* (quantity), *Davy Jones’ Organic Hot Chocolate* (revenue)  
- Store expansion: 3 new locations  

---

### 2. **📈 Sales by Product & Category**  
- Coffee is the top category (38.6% of sales), followed by Tea and Bakery  
- The dashboard ranks **top 10 products** by revenue and quantity  
- Store-level insights show that product preferences vary by location  

---

### 3. **🕒 Time of Day Revenue Analysis**  
- Peak sales occur between **9 AM and 11 AM**, with **10 AM** being the top revenue hour  
- Sales are minimal **before 7 AM and after 7 PM** (only 3.6% of total revenue)  
- This insight can drive decisions about **store opening hours and staffing schedules**  

---

### 4. **📅 Forecasting Full-Year Revenue**  
Using actual sales from Jan–Jun 2023, the model forecasts a total of **$1.4M** by end of year:  
- **Bankstown**: $476,942  
- **Newtown**: $463,928  
- **North Sydney**: $468,337  

These projections are based on recent upward trends in May and June—driven by growth in order size and volume.

---

## ✅ Recommendations  
- Adjust **opening/closing hours** to align with customer behavior and optimize labor costs  
- Double down on promoting top-performing products, especially **coffee and specialty drinks**  
- Analyze underperforming time slots and test marketing promotions to boost off-peak traffic  
- Use location-specific product insights to **tailor inventory and marketing per store**  
- Monitor month-over-month trends to fine-tune **forecasting assumptions** and reforecast quarterly  

---

## 📄 License  
Specify the license under which the project is released.

---

## 📬 Contact  
For questions, collaboration, or feedback:  
**Phil Dinh**  
📧 [phildinhdata@gmail.com](mailto:phildinhdata@gmail.com)

