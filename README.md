## **AdventureWorks Sales Performance Dashboard | Power BI Project**

Welcome to the **AdventureWorks Sales Performance Dashboard**! This interactive Power BI dashboard analyzes a rich dataset from Microsoft's AdventureWorks, a fictional bicycle manufacturing company. The goal is to uncover sales insights, evaluate performance across categories, regions, and resellers, and demonstrate business intelligence capabilities using Power BI.

---

## **Project Objective**

The primary aim of this project is to provide data-driven insights into sales performance across product categories, customer types, and geographic regions over multiple fiscal years. Key questions addressed include:

* How do sales trends evolve over time?
* Which reseller or channel drives the highest revenue?
* What is the sales distribution by region?
* How do different product categories perform?
* Where are the business opportunities geographically?

---
![image](https://github.com/user-attachments/assets/7e8ad054-3309-4730-a212-0bc787aea1ad)
---


## **Dataset Description**

The dataset used in this project comes from the **AdventureWorksDW** database and includes multiple tables such as:

* **Sales Order** – Contains order-level transaction details
* **Product** – Lists all product items including category and subcategory
* **Reseller** – Provides info on different reselling partners
* **Sales Territory** – Geographic segmentation
* **Date** – Date dimension to support time-series analysis

Key variables:

* **Sales Amount**: Revenue from each order
* **Order Quantity**: Number of units sold
* **Product Category**: Bikes, Components, Accessories, Clothing
* **Fiscal Year**: Grouped yearly for trend analysis
* **Reseller Type**: Warehouse, Value Added Reseller, etc.
* **Country-Region**: Geographic dimension for mapping sales

---

## **Dashboard Features**

The Power BI dashboard includes:

* **Sales Trend Line Chart**
  Showing yearly sales performance with comparative due date trends.

* **Map Visualization**
  Displays order quantities across global regions (Europe, North America, etc.).

* **Category & Subcategory Breakdown**
  Drillable matrix chart showing revenue per category and reseller type.

* **Total Sales KPI**
  Cumulative value of sales (\~₦109.8 million in your case).

---

## **Key Insights**

### 1. Top-Performing Category

* **Bikes** lead with over **₦94 million**, dominating total sales.

### 2. Reseller Analysis

* **Value Added Reseller** and **Warehouse** drive the bulk of revenue.

### 3. Geographic Performance

* Strong sales from **North America** and **Europe** regions.

### 4. Declining Trend

* Sales show a **downward trend** from FY2018 to FY2020, suggesting a need for performance evaluation or external factor consideration.

---

## 🧠 **Methodology**

1. **Data Modeling**

   * Relationship modeling between facts (Sales) and dimensions (Date, Product, Reseller).

2. **Data Cleaning**

   * Filtered null values, standardized formats, and aggregated sales by fiscal year and category.

3. **DAX Calculations**

   * Created measures for `Total Sales`, `Order Quantity`, and time intelligence.

4. **Visual Design**

   * Incorporated slicers, map visuals, matrix tables, and KPI cards with intuitive color schemes.

---

## 🛠 **Tools & Technologies**

* **Power BI Desktop** – Main dashboarding tool
* **DAX (Data Analysis Expressions)** – KPI and metric creation
* **Excel / AdventureWorksDW** – Data preparation
* **GitHub** – Documentation and version control

---

To use this project:

1. Open the `.pbix` file with Power BI Desktop
2. Explore the interactive filters and visuals
3. Modify DAX measures or visuals as needed for further analysis

---

## 🔗 **Acknowledgments**

* Microsoft for the [AdventureWorksDW database](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15)
* Power BI Community for continuous learning and support

---

