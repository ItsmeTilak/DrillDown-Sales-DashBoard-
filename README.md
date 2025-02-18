# 📊 Sales Dashboard - Power BI Project
#### Sales Dashboard
![SalesDashBoard](https://github.com/user-attachments/assets/b24cfcba-1adb-4fb4-bf31-0f11f6427c5f)
#### Drilldown Dashboard
![DrillDown](https://github.com/user-attachments/assets/21284bdf-d231-4bac-8f2b-a66376aca3aa)

 

## 🚀 Overview  
This Power BI project analyzes **sales data** using **interactive visualizations** and **drill-down dashboards** to gain insights into revenue, product performance, and employee contributions.  

### 🔗 Live Power BI Report  
🔗 [View the Power BI Dashboard](https://app.powerbi.com/links/RfBMecYYIa?ctid=6732707c-d33e-4d4f-bb04-1bab801a19db&pbi_source=linkShare&bookmarkGuid=a53bd7f5-532d-4941-9882-6fdeec5a4f12)  

---

## 📂 Dataset Details  
The dataset consists of **three key tables**:  

1. **Employee Master** – Contains employee details, including names and assigned supervisors.  
2. **Product Master** – Includes product names and unit prices.  
3. **Sales Data** – Records sales transactions, linking employees and products.  

📌 **Dataset File:** [`power_bi_sales_dataset.xlsx`](https://github.com/user-attachments/files/18850723/power_bi_sales_dataset.xlsx)

---

## 📊 Features & Insights  

### 🏆 **Key Features**  
✔️ **Dynamic Slicers** – Filter data by Date, Product, Employee, and Supervisor.  
✔️ **KPI Cards** – Show **Total Revenue** and **Total Units Sold**.  
✔️ **Drill-Down Visuals** – Dive deeper into **Supervisor and Employee-wise Revenue**.  
✔️ **Interactive Charts** – Line, Doughnut, and Bar charts for insightful analysis.  
✔️ **Action Buttons** – Navigate between dashboards with clickable images.  
✔️ **Table** – Sales data with revenue bars for quick insights.  
✔️ **Scroller** – Product data with price per unit visualised as an animating scrolling text.  
✔️ **Q&A Feature** – Ask natural language questions and get insights from Power BI.  
✔️ **Pinned Visuals** – Key insights pinned to a separate Power BI dashboard.  

---

## 🏗️ Data Transformation & Relationships  

To ensure proper **data relationships**, we established:  

- **One-to-Many Relationship**  
  - `Employee Master (EMP ID)` → `Sales Data (EMP ID)`  
  - `Product Master (Product ID)` → `Sales Data (Product ID)`  

- **Data Cleaning & Processing:**  
  - Date formats were standardized.  
  - Duplicate records were removed.  
  - Data types were corrected.  

---

## 📌 How to Use This Project  

### 🔹 **Power BI Desktop (Local Setup)**  
1. **Download Files**: Clone this repo or download the dataset.  
2. **Open Power BI**: Load `power_bi_sales_dataset.xlsx` into Power BI.  
3. **Build Relationships**: Ensure relationships are correctly mapped.  
4. **Customize Visuals**: Modify slicers, charts, or KPIs as needed.  

### 🔹 **Power BI Service (Online Sharing)**  
- Upload the report to **Power BI Service** for cloud access.  
- Pin visuals to **Power BI Dashboards** for quick insights.   

---

## 📢 Contributing  
Have ideas to improve this dashboard? Feel free to **fork** this repo and submit a **pull request**.  

---

## 🏆 Credits  
📌 **Dashboard Built Using:** Power BI  

💡 **Developed with a passion for Data Analytics!** 🚀
