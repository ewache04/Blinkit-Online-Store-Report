# **Blinkit Sales Insights**  

## **Table of Contents**  
1. [Business Requirement](#business-requirement)  
2. [ETL Process](#etl-process)  
3. [Chart’s Requirements](#charts-requirements)  
4. [Dashboard Overview](#dashboard-overview)  
5. [Future Recommendations](#future-recommendations)  
6. [Outcome](#outcome)  

---

## **Business Requirement**  
The goal of this project is to analyze sales data from Blinkit to uncover key insights into product performance, outlet performance, and customer preferences. This analysis will support better decision-making in product offerings, pricing, and inventory management.  

---

## **ETL Process**  

### 1. **Extract**  
- Downloaded the BlinkIT Grocery Data file from an online source.  
- Opened the file in Power BI for analysis.  

### 2. **Transform**  
- Cleaned data by removing discrepancies and irrelevant columns.  
- Addressed null values in the `Item Weight` column by deciding to retain them since they are not used in the analysis.    

### 3. **Load**  
- Loaded the cleaned data into Power BI.  
- Created various visualizations to represent insights effectively.  

---

## **Chart’s Requirements**  

### 1. **Total Sales by Fat Content**  
- **Objective:**  
   Analyze the impact of fat content on total sales to identify trends and product performance.  
- **Additional KPI Metrics:**  
   - Average Sales  
   - Number of Items  
   - Average Rating  
- **Chart Type:**  
Donut Chart  

---

### 2. **Total Sales by Item Type**  
- **Objective:**  
   Identify the performance of different item types in terms of total sales.  
- **Additional KPI Metrics:**  
   - Average Sales  
   - Number of Items  
   - Average Rating  
- **Chart Type:**  
Bar Chart  

---

### 3. **Fat Content by Outlet for Total Sales**  
- **Objective:**  
   Compare total sales across different outlets, segmented by fat content, to identify outlet-specific trends.  
- **Additional KPI Metrics:**  
   - Average Sales  
   - Number of Items  
   - Average Rating  
- **Chart Type:**  
Stacked Column Chart  

---

### 4. **Total Sales by Outlet Establishment**  
- **Objective:**  
   Evaluate how the age or type of outlet establishment influences total sales.  
- **Chart Type:**  
Line Chart  

---

## **Data Table**  
The table below shows the cleaned and transformed data used for analysis:  

**Data Table:**  
![Data Table](./images/analysis%20images/Blinkit_Data_Table.gif)  

---

## **Dashboard Overview**  
The following dashboard consolidates all key insights into a single view for a comprehensive analysis:  

**🔍 Complete Dashboard:**  
![Business Overview](./images/analysis%20images/Sales%20Overview.gif)  

---

## **Recommendations**  
**Optimize Inventory:**  
- Focus on high-performing product categories based on fat content and outlet performance.  

**Targeted Marketing:**  
- Tailor marketing strategies based on outlet size and product type performance.  

**Expand Outlet Network:**  
- Open new outlets in areas where high sales and positive performance indicators are observed.  

**Product Mix Strategy:**  
- Adjust the product mix based on the sales performance of different fat content categories.  

---

## **Outcome**  
This analysis will provide insights into product and outlet performance, enabling Blinkit to optimize product offerings, improve customer targeting, and enhance overall sales strategies.  

---