# 📊 Market Research Analytics Dashboard

## 📌 Overview  
The **Market Research Analytics Dashboard** delivers comprehensive insights into the performance of six marketing campaigns by analyzing sales trends, product preferences, customer demographics, and key purchase drivers. Built in **Power BI**, the dashboard empowers marketing and business leaders to make informed decisions around targeting, campaign optimization, and future strategy.

The report focuses on identifying which campaigns succeeded, who the customers are, and what factors influence purchase decisions—providing a clear roadmap for improving marketing effectiveness and driving sales growth.

---

## 🎯 Purpose  
This dashboard was developed in response to stakeholder demand for a performance analysis of recent marketing efforts, aiming to address key business questions:

- Which campaigns performed best in terms of purchases and revenue?
- Which products were most preferred across different campaigns?
- Who are our customers, and how do their demographics affect buying behavior?
- What factors drive purchase decisions across segments?

---

## 🧩 Dataset  
The dataset consists of transaction-level data across six marketing campaigns and includes:

- **Customer data**: demographics, education, marital status, income, and web activity  
- **Campaign metadata**: campaign IDs and accepted campaign labels  
- **Product info**: categories such as wine, meat, baked goods, sweets, etc.  
- **Sales data**: product quantity, revenue, and platform used (in-store, web, etc.)

The underlying data model follows a **star schema**, supporting one-to-many relationships and cross-filtering for interactive visual analysis.

---

## 🛠️ Tools Used  
- **Power BI**: For developing visual reports and calculating dynamic KPIs  
- **Power Query**: Used to clean, transform, and prepare the data model  
- **DAX**: For calculated columns, measures, and key influencer analytics  
- **PowerPoint**: To develop branded color schemes and report layout

---

## 📊 Dashboards  
![image](https://github.com/user-attachments/assets/d93c3ab5-0abe-4fda-9ed7-bc58599b9f88)


### Dashboard Breakdowns  
![image](https://github.com/user-attachments/assets/56217787-0fbf-4e54-850e-f444031dfca6)
![image](https://github.com/user-attachments/assets/5560a7ff-1cfa-4b5b-8f33-9afa45016113)
![image](https://github.com/user-attachments/assets/312c5704-a22d-449f-9412-7d8746210c78)

---

## 📌 Key Dashboard Sections  

### 1. **📈 Campaign Performance**  
- **Campaign 6** outperformed all others with **334 purchases** and generated the highest sales revenue (~$330K).  
- **Wine** emerged as the dominant product category across all campaigns.  
- **In-store purchases** led by a wide margin, highlighting strong brick-and-mortar engagement.  

> Campaign 6’s success is linked to strong alignment between product strategy (wine-focused) and platform use (in-store dominance), suggesting that high-value products perform better with face-to-face engagement.

---

### 2. **🧍‍♂️ Buyer Composition**  
- The majority of campaign participants are **married** (864) and hold **college/university degrees** (1127).  
- The average customer **income** is approximately **$52,247** and the **average age** is **56.2**.  
- Product preference shifts by **age group**:  
  - Older customers prefer wine.  
  - Meat purchases decline as age increases.  

> These insights provide clear direction for demographic-based targeting and tailored marketing messaging.

---

### 3. **📌 Purchase Drivers (Key Influencers)**  
- Customers with **income over $60,585** are **7.8x more likely** to accept Campaign 1.  
- **Web engagement** (less than 5 visits/month) and **marital status** also affect campaign acceptance.  
- Total sales decrease when **income drops below $40,049**, or customers have 2+ kids or teens at home.

> The **Key Influencers** visual enables the marketing team to isolate the strongest predictors of sales and campaign adoption.

---

## ✅ Recommendations  
- Focus future campaigns on the **50–80 age group**, especially for wine and baked goods promotions.  
- Prioritize **in-store promotions**, which drive the highest number of conversions.  
- Leverage Campaign 6’s strategy as a model for future launches—emphasizing wine, store presence, and demographic targeting.  
- Use the **Key Influencers** visuals to fine-tune segmentation strategies and predictive modeling.  
- Continue tracking buyer behaviors to adapt campaigns and personalize offers more effectively.

---

## 📄 License  
Specify the license under which the project is released.

---

## 📬 Contact  
For more information or collaboration:  
**Phil Dinh**  
📧 [phildinhdata@gmail.com](mailto:phildinhdata@gmail.com)
