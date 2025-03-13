# **Blinkit Sales Insights**  

## **📌 Table of Contents**  
1. [Business Requirement](#business-requirement)  
2. [ETL Process](#etl-process)  
   - [Extract Data](#1-extract-data)  
   - [Transform Data](#2-transform-data)  
   - [Load Data](#3-load-data)  
3. [Chart’s Requirements](#charts-requirements)  
   - [Total Sales by Fat Content](#1-total-sales-by-fat-content)  
   - [Total Sales by Item Type](#2-total-sales-by-item-type)  
   - [Fat Content by Outlet for Total Sales](#3-fat-content-by-outlet-for-total-sales)  
   - [Total Sales by Outlet Establishment](#4-total-sales-by-outlet-establishment)  
4. [Data Table](#data-table)  
5. [Dashboard Overview](#dashboard-overview)  
6. [Recommendations](#recommendations)  
7. [Outcome](#outcome)  
8. [Demo Video](#demo-video)  
9. [Project Structure](#project-structure)  

---

## **🚀 Business Requirement**  
The goal of this project is to analyze Blinkit's grocery sales data to uncover key insights related to product performance, outlet performance, and customer preferences.  

This analysis will enable better decision-making in:  
✅ Product offerings  
✅ Pricing strategies  
✅ Inventory management  

---

## **🔎 ETL Process**  

### **1. Extract Data**  
- Downloaded the Blinkit Grocery Data file from an online source.  
- Opened the file in Power BI for analysis.  

### **2. Transform Data**  
- Cleaned the data by removing discrepancies and irrelevant columns.  
- Retained null values in the `Item Weight` column since it’s not used for analysis.  

### **3. Load Data**  
- Loaded the cleaned data into Power BI.  
- Created multiple visualizations to effectively present the insights.  

---

## **📊 Chart’s Requirements**  

### **1. Total Sales by Fat Content**  
- **Objective:**  
   Analyze how fat content impacts total sales to uncover trends and assess product performance.  
- **Additional KPI Metrics:**  
   - Average Sales  
   - Number of Items  
   - Average Rating  
- **Chart Type:**  
   Donut Chart  

---

### **2. Total Sales by Item Type**  
- **Objective:**  
   Assess the sales performance of different item types.  
- **Additional KPI Metrics:**  
   - Average Sales  
   - Number of Items  
   - Average Rating  
- **Chart Type:**  
   Bar Chart  

---

### **3. Fat Content by Outlet for Total Sales**  
- **Objective:**  
   Compare total sales across different outlets, segmented by fat content, to identify outlet-specific trends.  
- **Additional KPI Metrics:**  
   - Average Sales  
   - Number of Items  
   - Average Rating  
- **Chart Type:**  
   Stacked Column Chart  

---

### **4. Total Sales by Outlet Establishment**  
- **Objective:**  
   Evaluate the influence of outlet establishment type or age on total sales.  
- **Chart Type:**  
   Line Chart  

---

## **📑 Data Table**  
The table below presents the cleaned and transformed data used for analysis:

**Data Table:**  
![Data Table](media/analysis%20images/Blinkit_Data_Table.gif)  

---

## **📈 Dashboard Overview**  
The following dashboard summarizes all key insights into a single view for comprehensive analysis:

**🔍 Complete Dashboard:**  
![Business Overview](media/analysis%20images/Sales%20Overview.gif)  

---

## **📢 Recommendations**  

✅ **Optimize Inventory:**  
- Focus on high-performing product categories based on fat content and outlet performance.  

✅ **Targeted Marketing:**  
- Tailor marketing strategies based on outlet size and product type performance.  

✅ **Expand Outlet Network:**  
- Open new outlets in high-performing regions where sales are strong.  

✅ **Product Mix Strategy:**  
- Adjust the product mix based on sales performance across different fat content categories.  

---

## **🏆 Outcome**  
This analysis provides valuable insights into product and outlet performance, enabling Blinkit to:  
✔️ Refine product offerings  
✔️ Enhance customer targeting  
✔️ Improve overall sales strategies  

---

## **🎥 Demo Video**  
👉 [Watch the Dashboard Demo Video](media/demo%20video/Dashboard%20Demo%20Video.mp4)  

---

## **📂 Project Structure**  
Here's the organized structure of the project:

```
Blinkit-Online-Store-Report/
├── Data/
│   └── BlinkIT Grocery Data.xlsx
├── media/
│   ├── analysis images/
│   │   ├── Blinkit Business Overview.pdf
│   │   ├── Blinkit_Data_Table.gif
│   │   ├── Sales Overview.gif
│   ├── demo video/
│   │   └── Dashboard Demo Video.mp4
│   └── background images/
├── reports/
│   └── blinkit-sales-report.pbix
├── static/
│   ├── script.js
│   └── styles.css
├── index.html
├── README.md
└── .gitattributes.gitattributes
```

### ✅ **Key Notes:**  
- Removed the duplicate `blinkit-sales-report.pbix` file.  
- All file paths are correctly referenced and organized.  

---

### 👨‍💻 **Author:** Jeremiah Ewache  
### 🌐 **GitHub:** [@ewache04](https://github.com/ewache04)  

---