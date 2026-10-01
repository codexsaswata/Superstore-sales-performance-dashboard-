# 📊 Super Store Sales Dashboard

An interactive **Power BI Sales Performance Dashboard** designed to analyze sales performance across products, categories, customer segments, shipping modes, regions, and time.

The project transforms raw sales transaction data into meaningful business insights using **Microsoft Power BI, KPI cards, interactive filters, geographic analysis, trend analysis, and sales forecasting**.

---

## 🎯 Project Objective

The objective of this project is to build an interactive sales analytics dashboard that helps users understand business performance and identify important sales trends.

The dashboard provides insights into:

* 💰 Overall sales performance
* 📦 Product and category performance
* 👥 Customer segment contribution
* 🚚 Shipping mode analysis
* 🌎 Regional sales performance
* 📈 Sales and profit trends
* 📊 Quantity performance
* 🚛 Average delivery performance
* 🔮 Future sales forecasting

---

## ✨ Key Features

### 💰 Sales Performance Analysis

The dashboard tracks overall sales performance using KPI cards.

**Key metrics:**

* Total Sales
* Total Quantity
* Average Delivery
* Sales across different business dimensions

---

### 📦 Category Analysis

Sales performance is analyzed across different product categories using interactive visualizations.

This helps identify:

* High-performing categories
* Low-performing categories
* Differences in category contribution

---

### 🛍️ Product Analysis

Product-level sales analysis is provided through interactive bar charts.

This helps understand which products contribute significantly to overall sales.

---

### 👥 Customer Segment Analysis

A donut chart is used to analyze sales based on customer segments.

This allows users to compare the contribution of different customer groups.

---

### 🚚 Shipping Mode Analysis

The dashboard analyzes sales across different shipping modes using:

* Clustered bar charts
* Donut charts

This provides an overview of sales distribution across shipping methods.

---

### 🌎 Regional Analysis

An interactive map visualizes sales and profit across different regions.

A **Region Slicer** allows users to filter the dashboard by region and explore regional performance.

---

### 📈 Time-Based Sales Analysis

Sales performance is analyzed over time using a stacked area chart.

The dashboard supports analysis by:

* Year
* Month
* Day

This makes it easier to identify sales trends and changes over time.

---

### 💹 Profit Trend Analysis

Profit performance is analyzed using the `Order_Date` hierarchy.

The dashboard allows analysis of:

* Monthly profit
* Daily profit
* Yearly profit

---

### 🔮 Sales Forecasting

A dedicated report page provides historical sales trend analysis and forecasting.

The forecast uses:

* `Order_Date`
* `Sales`
* Power BI forecasting functionality
* 95% confidence level

> Forecast values are analytical estimates based on historical data and should not be considered guaranteed future results.

---

## 📊 Dashboard Visualizations

| Visualization      | Analysis                   |
| ------------------ | -------------------------- |
| KPI Card           | Total Sales                |
| KPI Card           | Total Quantity             |
| KPI Card           | Average Delivery           |
| Donut Chart        | Sales by Segment           |
| Bar Chart          | Sales by Category          |
| Bar Chart          | Sales by Product           |
| Bar Chart          | Sales by Ship Mode         |
| Donut Chart        | Sales by Ship Mode         |
| Stacked Area Chart | Sales over Time            |
| Stacked Area Chart | Profit over Time           |
| Map                | Sales and Profit by Region |
| Slicer             | Region Filter              |

---

## 📄 Report Pages

### Page 1 — Super Store Sales Dashboard

The main dashboard provides an overview of sales performance.

It includes:

* Sales KPI
* Quantity KPI
* Average Delivery KPI
* Segment analysis
* Category analysis
* Product analysis
* Shipping mode analysis
* Sales trend
* Profit trend
* Regional map
* Region slicer

### Page 2 — Sales Forecast

The second page focuses on historical sales trends and forecasting.

It contains visualizations based on:

* Order Date
* Total Sales

Power BI forecasting is used to estimate future sales based on historical patterns.

---

## 🗂️ Data Model

The primary dataset used in the project is:

`Sales_Clean_Data`

### Important Fields

```text
Order_Date
Sales
Profit
Quantity
AvgDelivery
Segment
Category
Product
Ship_Mode
Region
```

These fields are used to create the dashboard KPIs, charts, filters, maps, and forecasting analysis.

---

## 🔄 Data Flow

```text
Raw Sales Data
       ↓
Data Cleaning
       ↓
Sales_Clean_Data
       ↓
Data Analysis
       ↓
KPI Calculations
       ↓
Power BI Visualizations
       ↓
Interactive Dashboard
       ↓
Trend Analysis
       ↓
Sales Forecast
       ↓
Business Insights
```

---

## 🎛️ Interactive Features

### Region Slicer

Users can select a region to filter the dashboard and analyze regional performance.

### Cross-Visual Interaction

Selecting data from one visualization can affect other dashboard visuals, allowing users to explore relationships between different sales dimensions.

### Date Hierarchy

The `Order_Date` field supports:

```text
Year
 └── Month
      └── Day
```

This allows sales and profit trends to be analyzed at different time levels.

---

## 📌 Key Business Questions

The dashboard can help answer questions such as:

* What is the overall sales performance?
* How many units were sold?
* Which categories generate the most sales?
* Which products contribute significantly to sales?
* How do customer segments contribute to sales?
* How are sales distributed across shipping modes?
* How are sales distributed across regions?
* How does profit change over time?
* How does sales performance change over time?
* What are the historical sales trends?
* What does the sales forecast indicate?

---

## 💡 Business Insights

The dashboard can support business analysis by helping organizations:

* Identify high-performing products
* Compare category performance
* Understand customer segment contribution
* Monitor regional sales
* Analyze shipping preferences
* Track sales trends
* Monitor profit trends
* Evaluate quantity performance
* Examine delivery performance
* Analyze historical trends for forecasting

---

## 🧮 Power BI Techniques Used

This project demonstrates practical knowledge of:

* Microsoft Power BI
* Data Cleaning
* Data Transformation
* Data Modeling
* KPI Cards
* Donut Charts
* Clustered Bar Charts
* Stacked Area Charts
* Map Visualization
* Slicers
* Date Hierarchies
* Aggregations
* Cross-filtering
* Time-Series Analysis
* Forecasting
* Dashboard Design
* Business Intelligence

---

## 📈 Forecasting

The project includes a dedicated sales forecasting page.

The forecast is generated using historical sales data based on:

```text
Order_Date
Sales
```

The configured forecast uses a **95% confidence level**.

Forecasting can be useful for:

* Sales planning
* Inventory planning
* Revenue estimation
* Business forecasting
* Identifying potential future trends

---

## 🛠️ Tools & Technologies

**Primary Tool**

* Microsoft Power BI

**Techniques**

```text
Power BI
Data Cleaning
Data Modeling
KPI Cards
Data Visualization
Map Visualization
Slicers
Date Hierarchy
Forecasting
Dashboard Design
Business Intelligence
```

---

## 📁 Repository Structure

```text
Super-Store-Sales-Dashboard/
│
├── sales performance dashboard 3.pbix
└── README.md
```

---

## 🎓 Skills Demonstrated

This project demonstrates practical knowledge of:

* Data Analytics
* Business Intelligence
* Microsoft Power BI
* Data Visualization
* Dashboard Development
* Sales Analysis
* KPI Development
* Time-Series Analysis
* Geographic Analysis
* Forecasting
* Business Analysis

---

## ⚠️ Limitations

* Dashboard performance depends on the quality and completeness of the underlying dataset.
* Forecast values are estimates based on historical sales patterns.
* Forecast results may change when new sales data is introduced.
* Dashboard results depend on the selected filters.
* The project is primarily intended for academic and demonstration purposes.

---

## 🔮 Future Improvements

Possible enhancements include:

* Additional KPI measures
* Customer-level analysis
* Profit margin analysis
* Year-over-year sales comparison
* Monthly and yearly growth calculations
* Advanced forecasting
* Customer segmentation
* Top and bottom product analysis
* Dynamic tooltips
* Additional slicers
* Drill-through pages
* Automated data refresh
* Power BI Service deployment

---

## 📌 Project Information

**Project Type:** Academic / Data Analytics / Business Intelligence

**Domain:** Sales & Business Analytics

**Tool:** Microsoft Power BI

**Dashboard:** Super Store Sales Dashboard

---

## 👨‍💻 Author

**Saswata Pati**

B.Tech IT Student | Aspiring Data Analyst

### 🔗 Connect With Me

* **GitHub:** [codexsaswata](https://github.com/codexsaswata)
* **LinkedIn:** [Saswata Pati](https://www.linkedin.com/in/saswata-pati-66614317b/)

---

## ⭐ Acknowledgement

This project was developed as an academic/practical demonstration of using **Microsoft Power BI for sales analysis, business intelligence, data visualization, interactive dashboard development, and forecasting**.

The project demonstrates how raw sales data can be transformed into meaningful visual insights for data-driven business analysis.
