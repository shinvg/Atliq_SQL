# AtliQ Hardwares - Sales & Product Performance Analysis for Consumer Goods Manufacturer

A SQL-based analytical project focused on extracting actionable insights from sales, product, and customer data to enable faster and more informed decision-making at AtliQ Hardwares.

---

## ❗ Business Problem

AtliQ Hardwares, a leading computer hardware company in India with growing international operations, lacks structured insights to support quick and data-informed decisions.

Leadership needed clarity on:

- How the product portfolio is evolving  
- Which segments are driving growth  
- How sales performance varies over time  
- Whether revenue is concentrated across channels, products, or customers  
- How discounting strategies are being applied  

The core challenge was to transform raw relational data into decision-ready insights using SQL.

---

## 💡 How to Explore this Project

- Each SQL query addresses a specific business question  
- Queries are structured to build insight across:
  - Markets  
  - Products  
  - Customers  
  - Sales trends  
- Focus is on analytical reasoning and business interpretation, not just query output  

---

## 📝 Project Overview

This project analyzes:

- Product expansion across years and segments  
- Sales performance across months and quarters  
- Channel contribution to revenue  
- Customer-level discounting patterns  
- Product and division-level performance  

**Goal:**  
Create a reliable analytical foundation and extract insights that can guide portfolio, pricing, and go-to-market decisions.

---

## 🔢 Data Sources

- `fact_sales_monthly` - Sales quantity data  
- `fact_gross_price` - Product pricing  
- `fact_manufacturing_cost` - Production cost  
- `fact_pre_invoice_deductions` - Discounts  
- `dim_product` - Product hierarchy  
- `dim_customer` - Customer and market data  

---

## 🛠 Tools & Techniques

- SQL (joins, aggregations, CTEs, window functions)  
- Conditional aggregation for YoY comparisons  
- Ranking functions for top product identification  
- Time-based transformations for trend analysis  

---

## 🔍 Analytical Approach

- Market expansion analysis using customer geography  
- Product portfolio growth using year-over-year comparisons  
- Segment-level contribution analysis  
- Time-series sales trend analysis  
- Channel-wise revenue breakdown  
- Customer-level discount benchmarking  

---

## 📊 Key Insights

### 1. Strong product expansion, but concentrated in specific segments

- Unique products increased from **245 (2020) → 334 (2021)**  
- **+36.33% growth**

Segment contribution:
- Accessories: +34 products  
- Notebook: +16  
- Peripherals: +16  
- Desktop: +15  

**Insight:**  
Portfolio expansion is heavily skewed toward Accessories.

**Implication:**  
Growth strategy is focused on high-volume accessory categories rather than broad diversification.

---

### 2. Product mix is dominated by a few large categories

- Notebook: 129 products  
- Accessories: 116 products  
- Peripherals: 84  

**Insight:**  
Portfolio is concentrated across a few major segments.

**Implication:**  
Operational complexity and dependency risk are higher in these categories.

---

### 3. Revenue is highly channel-dependent

- Retailer: 73.23% (~₹1219M)  
- Direct: 15.47%  
- Distributor: 11.30%  

**Insight:**  
Revenue is heavily dependent on retailer channels.

**Implication:**  
Limited control over pricing and customer relationships.

---

### 4. Sales performance is seasonal and volatile

- Near-zero sales during Mar–May 2020  
- Peak months between Sep–Nov (~₹20M monthly)

**Insight:**  
Sales are event-driven rather than stable.

**Implication:**  
Demand planning must account for seasonality and external shocks.

---

### 5. Q1 drives highest volume, Q3 underperforms

- Q1: 7.0M units  
- Q2: 6.6M  
- Q3: 2.0M  
- Q4: 5.0M  

**Insight:**  
Demand is uneven across quarters.

**Implication:**  
Inventory and supply planning must align with demand spikes.

---

### 6. Sales are concentrated in a few high-performing products

- Top products in some divisions reach ~700K units  
- Others significantly lower (~17K units)

**Insight:**  
Revenue depends on a narrow set of high-performing SKUs.

**Implication:**  
High risk concentration if top products decline.

---

### 7. Discounting is consistently high across key customers

- Flipkart: ~30.83%  
- Croma, Viveks, Ezone: ~30%  
- Amazon: ~29%  

**Insight:**  
Discounting is uniformly high across major clients.

**Implication:**  
Indicates weak pricing power and margin pressure.

---

### 8. Manufacturing costs vary significantly

- Lowest: ₹0.89  
- Highest: ₹240.54  

**Insight:**  
Cost structure is highly diverse.

**Implication:**  
Profitability varies significantly across products.

---

### 9. Broad APAC market presence

Markets include:
- India, Japan, Indonesia, South Korea, Australia  

**Insight:**  
Company operates across multiple international markets.

**Implication:**  
Opportunity for region-specific strategies.

---

## 🧠 What This Project Demonstrates

- Translating business problems into SQL queries  
- Combining multiple datasets for insight generation  
- Moving from raw data to business decisions  
- Identifying key drivers of growth and revenue  

---

## ⚠️ Scope & Limitations

- No profitability analysis  
- No predictive modeling  
- No customer segmentation  

Focus was on descriptive and diagnostic analytics.

---

## 🚀 Potential Extensions

- Profitability and margin analysis  
- Customer segmentation  
- Channel-wise margin comparison  
- Dashboard development (Power BI / Tableau)  

---

## 📌 Deliverables

- 10 SQL queries solving business problems  
- Clean analytical outputs  
- Insight-driven business narrative  

---

## ✔️ Conclusion

This project demonstrates my ability to:

- Use SQL for business data analysis  
- Build structured insights from raw data  
- Identify growth, pricing, and sales patterns  
- Support decision-making with data  

---

## 📬 Contact

LinkedIn: https://www.linkedin.com/in/gaurav-b-166a19251/
Email: gauravbidlan0786@gmail.com
