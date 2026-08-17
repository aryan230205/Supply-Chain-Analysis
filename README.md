# 📦 Supply Chain Analysis

Welcome to the **Supply Chain Analysis** project by **Aryan Ghosh**!

This project is an end-to-end **Data Analytics and Business Intelligence case study** focused on analyzing supply chain operations across product sales, inventory, manufacturing, suppliers, transportation, shipping, and product quality.

Using **Python, MySQL, Excel, and Power BI**, the project transforms raw supply chain data into meaningful business insights and actionable recommendations aimed at improving operational efficiency, reducing costs, and increasing profitability.

---

## 📌 Objective

The primary objective of this project is to analyze supply chain data and identify opportunities to improve:

* 💰 Revenue and profitability
* 📦 Inventory and stock management
* 🏭 Manufacturing efficiency
* 🚚 Transportation and shipping performance
* 🤝 Supplier performance
* ❌ Product quality and defect rates
* 📍 Regional sales performance
* ⏱️ Lead times and delivery efficiency

The project simulates a real-world analytics workflow where raw operational data is transformed into **business-focused insights for decision-making**.

---

# 🧰 Tools & Technologies Used

| Tool           | Purpose                                                                           |
| -------------- | --------------------------------------------------------------------------------- |
| **Python**     | Data cleaning, exploratory data analysis, statistical analysis, and visualization |
| **Pandas**     | Data manipulation and preprocessing                                               |
| **NumPy**      | Numerical analysis and calculations                                               |
| **Matplotlib** | Data visualization                                                                |
| **Seaborn**    | Statistical visualization                                                         |
| **MySQL**      | Data querying, aggregation, KPI calculation, and business analysis                |
| **Excel**      | Data analysis, pivot tables, dashboarding, and KPI validation                     |
| **Power BI**   | Interactive dashboard development and business intelligence                       |

---

# 📂 Dataset Summary

The supply chain dataset contains **24 columns and 100+ records** covering different aspects of supply chain operations.

### Key Areas Covered

* 🛒 Product information
* 💰 Product pricing
* 📈 Sales and revenue
* 📦 Product availability
* 🏭 Manufacturing costs
* ⏱️ Manufacturing lead times
* 📋 Order quantities
* 📊 Production volumes
* ❌ Inspection and defect rates
* 🚚 Shipping costs
* 🛳️ Transportation modes
* 📍 Routes and locations
* 🚛 Shipping carriers
* 🤝 Supplier information
* 👥 Customer demographics

The dataset enables analysis of **revenue generation, manufacturing expenses, inventory levels, transportation costs, supplier performance, and product quality**.

---

# 🔍 Exploratory Data Analysis — Python

Python was used for the initial exploration and preparation of the dataset.

## Key Activities

### 1. Dataset Loading

* Loaded the supply chain dataset
* Examined the structure and dimensions of the dataset
* Reviewed available columns and data types

### 2. Data Cleaning

* Checked for missing values
* Identified duplicate records
* Validated data types
* Prepared the dataset for further analysis

### 3. Exploratory Data Analysis

Performed descriptive and grouped analysis to understand:

* Sales performance
* Product distribution
* Revenue generation
* Customer demographics
* Product availability
* Inventory levels
* Manufacturing performance
* Shipping performance
* Product quality

### 4. Data Visualization

Used **Matplotlib and Seaborn** to identify trends, relationships, and patterns across the supply chain.

---

# 📊 Sales Analysis

The sales analysis focuses on understanding product demand, revenue generation, and customer purchasing patterns.

### Key Analysis

* Analyzed products sold and revenue generated
* Compared sales performance across product categories
* Examined customer demographics
* Evaluated product availability and stock levels
* Identified high-demand product categories

### Business Objective

The analysis helps determine which products contribute most to revenue and where inventory and marketing efforts can be prioritized.

---

# ⚙️ Operational Analysis

The operational analysis focuses on manufacturing and inventory efficiency.

### Key Analysis

* Analyzed lead times
* Examined order quantities
* Evaluated production volumes
* Compared manufacturing costs
* Analyzed inventory availability
* Examined inspection results and defect rates

### Business Objective

The objective is to identify operational bottlenecks, reduce unnecessary costs, improve inventory planning, and minimize product quality issues.

---

# 🚚 Shipping & Logistics Analysis

The shipping analysis evaluates the efficiency and cost of different logistics options.

### Key Analysis

* Compared shipping costs across carriers
* Analyzed transportation modes
* Evaluated shipping routes
* Compared shipping times
* Analyzed carrier performance
* Examined transportation costs against revenue

### Business Objective

The analysis helps identify cost-effective transportation methods and shipping carriers while maintaining efficient delivery times.

---

# 🗄️ MySQL Analysis

MySQL was used to perform structured business analysis and answer specific supply chain questions.

## 📊 Total Revenue by Product Type

Calculated total revenue generated by each product category to identify the major revenue contributors.

---

## 🚚 Shipping Costs by Carrier

Calculated the average shipping cost for each shipping carrier to compare their cost efficiency.

---

## ⏳ Lead Times by Supplier

Calculated the average lead time for each supplier to evaluate supplier reliability and operational efficiency.

---

## 🌍 Total Products Sold by Location

Analyzed the total number of products sold across different locations to identify regional demand patterns.

---

## 🔍 Defect Rates by Inspection Results

Analyzed defect rates across different inspection outcomes to identify product quality issues.

---

## 💰 Product Profitability Ranking

Ranked products based on profitability using:

**Profitability = Revenue Generated − Manufacturing Cost − Shipping Cost**

This helps identify products that contribute most to overall profitability.

---

## 📦 Supplier Performance Analysis

Compared supplier-level average lead times against the overall average lead time to identify suppliers requiring operational attention.

---

## 🏆 Top 5 Shipping Carriers by Cost Efficiency

Identified the five shipping carriers with the lowest average shipping cost per product shipped.

This analysis helps support data-driven logistics and carrier-selection decisions.

---

# 📈 Excel Analysis

Excel was used for data validation, exploratory analysis, KPI calculations, and dashboard development.

### Key Activities

* Data validation
* Pivot table analysis
* KPI calculations
* Product-level analysis
* Carrier comparison
* Transportation analysis
* Sales analysis
* Defect-rate analysis
* Inventory analysis

---

# 📊 Excel Dashboard

The Excel dashboard provides a consolidated view of important supply chain metrics and performance indicators.

### Key Insights

* 🧴 **Skincare** products generate the highest revenue and are the most profitable category.
* 💇 **Haircare** follows skincare in terms of overall performance.
* 💄 **Cosmetics** contribute comparatively lower revenue.
* 🚚 **Carrier C** has the highest average shipping cost.
* 🚛 **Carrier B** is the most cost-effective shipping carrier based on average shipping cost.
* 🛳️ **Air transportation** has comparatively higher shipping costs.
* 🌊 **Sea transportation** provides a more economical transportation option.
* 📍 **Kolkata and Delhi** record the highest product sales among the analyzed locations.
* 📍 **Bangalore** records the lowest number of products sold.
* ❌ **Haircare** has the highest reported defect rate at approximately **37%**.
* 🏭 **Skincare** has the highest manufacturing cost among the analyzed product categories.

---

# 📊 Power BI Dashboard

The Power BI dashboard was developed to provide an interactive view of supply chain performance.

The dashboard combines **KPIs, charts, graphs, and slicers** to allow users to explore the data dynamically.

---

## 🎯 Key Performance Indicators

The dashboard includes the following KPIs:

| KPI                         |   Value |
| --------------------------- | ------: |
| 💰 Total Revenue            | 577,000 |
| 💵 Average Product Price    |   49.46 |
| 📦 Total Products Sold      |  46,000 |
| 🏭 Manufacturing Cost       |   47.27 |
| 📦 Total Available Products |   4,840 |
| 💼 Total Stock Value        |   4,777 |

---

# 📈 Power BI Visualizations

The dashboard contains the following major visualizations:

### 1. Product Performance

**Average Defect Rate, Manufacturing Lead Time, and Manufacturing Cost by Product**

Used to compare product categories across operational and quality metrics.

---

### 2. Customer Demographics Analysis

**Customer Demographics vs. Number of Products Sold by Product Type**

Used to understand purchasing behavior across customer groups.

---

### 3. Revenue & Sales Analysis

**Total Revenue Generated by Product Type vs. Total Products Sold**

Used to compare sales volume with revenue contribution.

---

### 4. Price vs. Manufacturing Cost

**Average Manufacturing Cost vs. Average Price by Product Type**

Used to understand the relationship between product pricing and production expenses.

---

### 5. Transportation Analysis

**Transportation Modes vs. Routes with Average Cost**

Used to evaluate logistics costs across different transportation modes and routes.

---

### 6. Quality Analysis

**Defect Rate vs. Inspection Rate by Product Type**

Used to identify product categories with potential quality-control issues.

---

### 7. Shipping Efficiency

**Transportation Modes and Shipping Carriers with Average Shipping Time**

Used to compare shipping efficiency across carriers and transportation methods.

---

# 🎛️ Interactive Power BI Slicers

The dashboard includes interactive slicers for:

* Product Type
* Transportation Mode
* Shipping Carrier
* Routes
* Supplier Name

These slicers allow users to dynamically filter the dashboard and perform deeper analysis.

---

# 💡 Key Business Insights

## 1. Product Category Performance

Skincare records the highest number of products sold and contributes approximately **45% of the business**, followed by:

* Haircare — **29%**
* Cosmetics — **25%**

This indicates strong demand for skincare products and highlights the importance of maintaining adequate inventory for this category.

---

## 2. Customer Demographics

The customer demographic analysis indicates differences in purchasing behavior across product categories.

Female customers show stronger purchasing activity for skincare and cosmetics, while male customers show relatively balanced demand across haircare and cosmetics.

The unknown demographic group also represents a significant volume of purchases across product categories.

Overall, **skincare remains the strongest-performing category across customer groups**.

---

## 3. Inventory & Availability

The analysis indicates that haircare and skincare maintain relatively similar inventory quantities, while cosmetics maintain slightly lower stock levels.

Skincare shows stronger product availability, supporting faster fulfillment and shipment.

Haircare and cosmetics show comparatively higher stock levels combined with lower availability, suggesting potential opportunities to improve inventory planning and operational efficiency.

---

## 4. Manufacturing & Lead Times

Skincare products have relatively high order quantities and longer lead times, which may be associated with higher production requirements.

Haircare products also demonstrate relatively high production volumes and longer lead times.

This highlights the importance of aligning production planning with expected demand to avoid delays and inventory imbalances.

---

## 5. Product Quality

The analysis indicates relatively high defect rates across the product categories.

Haircare records the highest reported defect rate, making it a potential priority area for quality-control improvements.

Reducing defect rates could help decrease production losses and improve overall customer satisfaction.

---

## 6. Shipping Carrier Performance

The analysis of shipping carriers indicates that **Carrier B generates higher revenue despite having comparatively higher shipping costs**.

This suggests that carrier selection should not be based solely on shipping cost; revenue contribution, delivery performance, and operational efficiency should also be considered.

---

## 7. Transportation Efficiency

The analysis indicates that **road transportation** provides strong overall efficiency among the analyzed transportation modes.

Carrier B also demonstrates strong shipping-time performance.

This suggests that combining efficient carriers with appropriate transportation modes could help improve delivery performance while controlling logistics costs.

---

# 🚀 Business Recommendations

Based on the analysis, the following recommendations can be considered:

### 📦 1. Optimize Inventory

Maintain higher availability for high-demand categories such as skincare while reducing unnecessary inventory accumulation in slower-moving categories.

### 🏭 2. Improve Manufacturing Efficiency

Investigate the causes of longer manufacturing lead times and identify opportunities to streamline production processes.

### ❌ 3. Reduce Defect Rates

Prioritize quality-control improvements for haircare products due to their relatively high defect rate.

### 🚚 4. Optimize Carrier Selection

Evaluate shipping carriers using a combination of:

* Shipping cost
* Delivery time
* Revenue contribution
* Reliability

rather than considering shipping cost alone.

### 🌍 5. Focus on High-Demand Locations

Prioritize inventory and distribution planning in high-performing locations such as Kolkata and Delhi while investigating the reasons for lower sales in Bangalore.

### 📈 6. Align Production With Demand

Use historical sales and demand patterns to improve production planning and minimize both stockouts and excess inventory.

---

# 📁 Project Structure

```text
📦 Supply-Chain-Analysis/
│
├── 🐍 Supply Chain Analysis.ipynb
│
├── 🗄️ Supply Chain Analysis - MySQL.sql
│
├── 📈 Supply Chain Analysis.xlsx
│
├── 📊 Supply Chain Analysis.pbix
│
└── 📖 README.md
```

---

# 🎯 Skills Demonstrated

### Data Analytics

* Exploratory Data Analysis
* Data Cleaning
* Data Transformation
* KPI Development
* Trend Analysis
* Business Analysis
* Data Visualization
* Data Storytelling

### Technical Skills

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* MySQL
* Microsoft Excel
* Power BI
* SQL

### Business Skills

* Supply Chain Analytics
* Revenue Analysis
* Inventory Analysis
* Manufacturing Analysis
* Logistics Optimization
* Supplier Performance Analysis
* Cost Analysis
* Data-Driven Decision Making

---

# 👨‍💻 About Me

**Aryan Ghosh**

🎓 Engineering Student at **NIT Raipur**
📊 Aspiring **Data Analyst / AI Analyst**
💡 Interested in **Data Analytics, Business Intelligence, Finance, and Data-Driven Decision Making**

I enjoy working with data to identify patterns, solve business problems, and transform complex datasets into actionable insights.

### Connect With Me

📧 **[aryanghosh010@gmail.com](mailto:aryanghosh010@gmail.com)**

🐙 **GitHub:** `aryan230205`

---

# 🔗 Project Dashboard

### Power BI Dashboard

[View Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzgzMTQ1YjItMmIwZC00MTBmLWJiOTUtYzZlNTFmNzYyMzA2IiwidCI6ImRmODY3OWNkLWE0MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

---

# 🙏 Thank You!

Thank you for exploring the **Supply Chain Analysis** project.

This project demonstrates how **Python, SQL, Excel, and Power BI** can be combined to transform raw supply chain data into meaningful business insights and support data-driven operational decisions.

**Built with Python • MySQL • Excel • Power BI**
