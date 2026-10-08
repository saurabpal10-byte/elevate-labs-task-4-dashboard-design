# Elevate Labs – Task 4: Dashboard Design

## 📊 Sales & Profit Performance Dashboard

This project was completed as part of the **Data Analyst Internship at Elevate Labs**.

The objective of this task was to design an interactive business dashboard using **Microsoft Power BI** to help stakeholders monitor sales performance, profitability, growth, customer segments, product categories, and regional performance.

---

## 🎯 Objective

The main objective of this project was to create an interactive dashboard that:

- Tracks important business KPIs
- Provides sales and profit analysis
- Shows time-series trends
- Allows users to filter data interactively
- Highlights important business insights
- Supports data-driven business decisions

---

## 🛠️ Tools Used

- **Microsoft Power BI**
- **DAX**
- **Microsoft PowerPoint**
- **CSV Dataset**

---

## 📂 Dataset

The project uses the **Sample Superstore** sales dataset.

The dataset contains sales transaction information including:

- Order Date
- Ship Date
- Customer Segment
- Region
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

### Dataset Size

- **9,994 rows**
- **21 columns**

---

## 📈 Dashboard KPIs

The dashboard contains four major KPI cards:

| KPI | Value |
|---|---:|
| Total Sales | 2.30M |
| Total Profit | 286.40K |
| Sales Growth | 20.4% |
| Profit Margin | 12.5% |

These KPIs provide a quick overview of the overall business performance.

---

## 📊 Dashboard Visualizations

The Executive Dashboard includes:

### 1. Monthly Sales Trend

A time-series line chart showing changes in sales over time.

### 2. Monthly Profit Trend

A time-series visualization showing monthly profit performance.

### 3. Sales by Category

Compares sales performance across:

- Furniture
- Office Supplies
- Technology

### 4. Profit by Region

Compares profitability across:

- Central
- East
- South
- West

### 5. Sales by Customer Segment

Analyzes sales contribution from:

- Consumer
- Corporate
- Home Office

---

## 🎛️ Interactive Filters

The dashboard contains interactive slicers for:

- **Order Date**
- **Region**
- **Category**

These filters allow users to dynamically analyze different parts of the dataset.

---

## 🔗 Dashboard Navigation

The Power BI report contains navigation between:

- **Executive Dashboard**
- **Business Insights & Recommendations**

This allows users to move between the analytical dashboard and the business interpretation page.

---

## 💡 Key Business Insights

### Sales Performance

Technology is the strongest sales-generating category and is an important contributor to overall revenue.

### Profitability

West is the most profitable region, while Central shows negative profit and requires further investigation.

### Customer Segments

Consumer customers contribute the largest share of sales, making this an important customer segment for business growth.

### Sales Trends

Monthly sales patterns help identify periods of stronger and weaker demand and can support future sales and inventory planning.

---

## 💼 Business Recommendations

1. **Prioritize Technology Sales**  
   Continue investing in high-performing technology products and related promotions.

2. **Improve Central Region Profitability**  
   Review pricing, discounting, product mix, and operating costs in the Central region.

3. **Focus on High-Value Customer Segments**  
   Use targeted campaigns and retention strategies for the strongest revenue-generating customer segment.

4. **Use Sales Trends for Planning**  
   Use monthly sales patterns to support inventory, marketing, and sales planning.

---

## 📁 Project Structure

```text
elevate-labs-task-4-dashboard-design/
│
├── README.md
│
├── powerbi/
│   └── Task_4_Dashboard.pbix
│
├── dataset/
│   └── Sample - Superstore.csv
│
├── screenshots/
│   ├── executive_dashboard.png
│   └── business_insights.png
│
└── presentation/
    └── Task_4_Dashboard_Summary.pptx
