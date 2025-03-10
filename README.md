# Maven Roasters Project

## Project Background and Overview
Maven Roasters is a specialty coffee shop chain with three locations in New York City—Astoria, Hell’s Kitchen, and Lower Manhattan—offering premium coffee, tea, and baked goods.  
I'm partnering with the Head of Operations to analyze performance data and provide strategic recommendations to enhance sales, optimize product offerings, and refine marketing strategies across all three locations.  

This analysis focuses on uncovering purchase behaviors, identifying sales trends, and pinpointing opportunities for revenue growth. Additionally, we aim to improve operational efficiency by optimizing staffing and inventory management.  

By leveraging interactive dashboards and data-driven insights, we will enable smarter business decisions and opportunities that drive sales and streamline daily operations.  

## Key Business Metrics:
- **Total Transaction Volume:** Daily sales transactions across all locations  
- **Monthly Revenue Performance (MoM Trends):** Total revenue generated per store month-over-month, identifying trends  
- **Hourly and Daily Sales Trends:** Identifying peak and low-traffic periods throughout the week  
- **Product Performance:** Top- and bottom-performing products by location  

## Data Structure Overview
![Maven Roasters ERD](https://github.com/romandkuang/Maven-Roasters-Project/blob/main/maven%20roasters%20erd.drawio%20(1).png?raw=true)

## Executive Summary
Maven Roaster's sales analysis, based on **149K transactions over a 6-month period (Jan – June 2023),** reveals a total revenue of **$700K** across three locations.  
Revenue is relatively evenly distributed among the three locations:  
- **Hell's Kitchen**: 33.84% ($236,511)  
- **Astoria**: 33.23% ($232,243)  
- **Lower Manhattan**: 32.92% ($230,057)

Tea, coffee, and espresso emerge as the top three product categories at all locations, consistently driving the highest sales.  
The analysis indicates that peak sales occur during **morning hours (7-10 AM)**, with a noticeable decline in performance throughout February across all locations.  

Furthermore, sales show a **significant drop after 10 AM**, highlighting an opportunity for operational improvement.  
To address these trends, Maven Roaster can:  
- Optimize staffing levels during peak hours  
- Explore new menu items that cater to customer preferences  
- Launch targeted promotions and specials during off-peak periods  

By taking these actions, Maven Roaster can enhance overall business performance, maximize revenue, and better meet customer demand.  

---

## **Insights Deep Dive**  

### **Total Revenue Volume**
- **Balanced Revenue Distribution Across Locations:**  
  Revenue is closely distributed across locations, with each contributing approximately **one-third** of total revenue.  
- **Hell’s Kitchen slightly outperforms the other locations**:  
  - Hell’s Kitchen: **$236,511**  
  - Astoria: **$232,243**  
  - Lower Manhattan: **$230,057**  
- The revenue gap is minimal, showing **consistent performance across locations** and potential for further optimization.

| <img src="https://github.com/romandkuang/romandkuang/blob/main/assets/img/total_revenue_hellskitchen.png?raw=true" width="900"> | <img src="https://github.com/romandkuang/romandkuang/blob/main/assets/img/total_revenue_astoria.png?raw=true" width="900"> |
| --- | --- |
| <img src="https://github.com/romandkuang/romandkuang/blob/main/assets/img/total_revenue_lowermanhattan.png?raw=true" width="900"> |

<p align="center">
  <img src="https://github.com/romandkuang/romandkuang/blob/main/assets/img/bar%20chart%20total%20revenue%20maven%20roastesr.png" width="600">
</p>


### **Monthly Revenue Performance (MoM Trends)**
- **February Drop Across Locations:**  
  - Astoria (-8.09%) had the sharpest decline, followed by Hell’s Kitchen (-7.55%) and Lower Manhattan (-4.61%).  
- **Strong Recovery in March:**  
  - Sales increased **28-31%** across all locations.  
- **Peak Performance in May:**  
  - All three locations experienced **30-32% growth**.  
- **Slight Increase in June:**  
  - Sales slowed to **5-8%** growth, the only **single-digit** increase in the dataset.  

### **Hourly and Daily Sales Trends**
- **Double Surge at 7 AM:**  
  - Hell’s Kitchen: **+105.1%**  
  - Lower Manhattan: **+98.5%**  
  - Astoria (opens at 7 AM): **+18.8%** (7-8 AM)  
- **Mid-day Drop After 10 AM:**  
  - Sales decline **-35% to -56%** across locations.  
  - **Sharpest decline at 11 AM:**  
    - Lower Manhattan: **-56.2%**  
    - Hell’s Kitchen: **-48.3%**  
- **Sales Fluctuate After 12 PM:**  
  - Astoria remains stable, while Hell’s Kitchen and Lower Manhattan experience irregular swings.  
- **Evening Sales (6-8 PM) Decline:**  
  - **Lower Manhattan:** -43.5% (6 PM), -91.2% (7 PM)  
- **Varied Weekly Performance Across Locations:**  
  - Hell’s Kitchen: Growth on **Tuesdays (+5.2%) and Sundays (+7.3%)**  
  - Astoria: Growth on **Tuesdays (+4.8%)**, steady throughout the week.  
  - Lower Manhattan: **Minimal increases (1% to 2.3%) throughout the week.**  

### **Product Performance**
- **Brewed Chai Tea is Astoria’s top-selling product**  
  - **6,293 transactions (12.7% of total sales)**  
- **Espresso is the top seller in Hell’s Kitchen and Lower Manhattan**  
- **Top 3 product types across all locations:**  
  - **Chai Tea, Coffee, and Espresso** → Highlights customer preference for signature beverages.  
- **Bottom-performing products:**  
  - Astoria: **Green Bean Coffee (5.7%)**  
  - Lower Manhattan: **Green Bean Coffee (4.6%)**  
  - Hell’s Kitchen: **Green Tea (4.97%)**  

---

## **Recommendations**
Based on the insights and findings above, we would recommend the stakeholder team to consider the following: 
### **1. Target High-Value Products**
- **Leverage Popularity:**  
  - Promote **top-selling products (Brewed Chai Tea, Barista Espresso)** in marketing campaigns to attract more customers.  
- **Bundling & Special Offers:**  
  - On **busy days**, bundle bestsellers with pastries to **increase transaction value**.  
  - On **slower days**, offer **BOGO deals** to **encourage bulk purchases and drive sales**.  

### **2. Staffing Optimization & Inventory Adjustments**
- **Staffing Adjustments:**  
  - Increase staff **during peak hours** to reduce wait times.  
  - Scale back staffing **during low-traffic hours** to optimize labor costs.  
- **Inventory Adjustments:**  
  - Stock high-demand products **on peak days**.  
  - Reduce stock for **underperforming products** and offer discounts.  
  - Consider **removing consistently low-performing products** from the menu.  

---

## **Clarifying Questions, Assumptions, and Caveats**
- **Missing Monthly Data:**  
  - Dataset only includes **January–June** transactions. No data beyond June, limiting the ability to track **seasonal trends**.  
- **Lack of Promotional Data:**  
  - Sales data does not indicate active promotions, making it difficult to **attribute changes in sales to marketing efforts**.  
- **Blank Transaction Data (6 AM & 8 PM in Astoria):**  
  - Assumed to be due to store hours. Further clarification needed.  
