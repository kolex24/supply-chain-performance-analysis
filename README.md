# Supply Chain Performance Analysis
> An End-to-End Power BI Business Intelligence Dashboard that enables stakeholders to monitor key supply chain metrics, evaluate operational performance, identify quality and inventory risks, and support data-driven decision-making.
---

## Dataset Overview
This project analyzes a manufacturing supply chain dataset containing information on:
- Product Types
- Suppliers
- Inventory Levels
- Revenue
- Manufacturing Costs
- Shipping Costs
- Transportation Modes
- Lead Time
- Defect Rates
- Inspection Results
- Regional Sales
  
The dataset was transformed using Power Query and analyzed with DAX measures in Power BI.

---
## Business Problem
A manufacturing company faced challenges in monitoring sales performance, logistics efficiency, inventory optimization, and product quality across its supply chain. Decision-makers lacked a centralized view of operational performance, making it difficult to identify inefficiencies and prioritize improvement efforts.

---

## Business Objectives
- Evaluate overall business performance by analyzing revenue generated and products sold.
- Identify the product categories contributing the highest and lowest revenue.
- Analyze transportation costs across shipping routes and determine whether higher logistics costs are justified by revenue generated.
- Evaluate regional sales performance to identify high-performing and underperforming markets.
- Investigate defect rates by product, supplier, and transportation mode to identify quality improvement opportunities.
- Assess supplier performance based on manufacturing cost, lead time, and product quality.
- Examine shipping carriers and transportation modes to determine the most cost-effective delivery methods.
- Monitor inventory availability and stock levels to identify risks of stock shortages or overstocking.
- Compare manufacturing costs against revenue to identify products with poor profitability.
- Provide strategic recommendations that improve operational efficiency, reduce costs, and increase revenue.

---
## Tools Used
- Power BI
- Power Query
- DAX

---
## Dashboard Overview
**Executive Overview**

Purpose: Provide executives with a high-level overview of operational performance.

**KPIs**
- Revenue
- Manufacturing Cost
- Defect Rate
- Order Quantity

**Business Questions:**
- How is the business performing?
- Which supplier contributes the most revenue?
- Which region generates the highest revenue?
- Which product generates the most revenue?

**Sales Performance**

**KPIs**
- Number of Product Sold
- Production Volume
- Price
- Availability
- Revenue

**Business Questions:**
- Which region have the most number of product sold?
- Which product generate the highest production volume and price?
- Which product generate the most most revenue?
- Which customer demographic contribute the most to the revenue?

**Supply Chain**

**KPIs**
- Transportation Cost
- Shipping Cost
- Lead Time
- Shipping Times
- Defect Rates

**Business Questions:**
- Which transportation route is the most expensive and have the highest revenue?
- Which carrier have the highest shipping cost?
- Which carrier have the most lead times and shipping times?
- Which transportation mode have the lesat cost?
- Which supplier have the highest shipping cost?
- Which carrier have the most defect rates?

**Inventory**

**KPIs**
- Availability
- Products Needing Reorder
- Inventory Value
- Inventory Turnover
- Reorder Point
- Stock
- Stock Coverage
- Average Daily Demand

**Business Questions:**
- Which product have the most stock and reorder point?
- Which product generate the most inventory value?
- Which region have the highest inventory value?
- Which product have the longest days of stock?
- Which external partners require immediate intervention?

**Quality**

**KPIs**
- Inspection Rate
- Defective Items
- Defect Rate
- Manufacturing Cost
- Inspection Pass Rate
- Revenue

**Business Questions:**
- Which product category is driving the most inspection failure?
- Does how we shi affect product quality?
- Which suppliers are consistently delivering defective products?
- Are certain carriers damaging goods in transit?
- Which region has the worst quality performance? 

---

## Data Cleaning

The dataset was cleaned using Power Query by:

- Removing duplicate records
- Handling missing values
- Correcting data types
- Creating calculated columns
- Building relationships
- Creating DAX measures for KPI reporting

---

## Business Insight & Recommendation

**Executive Overview**

**Insight**:
Supplier 1 is the company's largest revenue contributor, accounting for $157.53K (27%) of total revenue. Mumbai is the highest-performing market, indicating strong regional demand. Although the overall defect rate remains relatively low (2.28%), maintaining product quality should remain a priority as production scales.

**Action:**
- Strengthen partnerships with Supplier 1 while reducing dependency by improving the performance of lower-contributing suppliers.
- Increase inventory allocation to Mumbai to support sustained customer demand.
- Continue monitoring defect rates to maintain product quality as sales grow.

**Sales Performance**

**Insight:**
Skincare products are the primary revenue driver, suggesting they represent the company's strongest product category. Kolkata records the highest sales volume, highlighting it as a key market for future inventory planning and marketing investment.

**Action:**
- Prioritize production of skincare products.
- Expand promotional activities in high-performing locations.
- Investigate why Bangalore has comparatively lower sales performance.

**Supply Chain**

**Insight:**
Route A generates the highest revenue but also incurs the highest transportation cost, suggesting that additional cost analysis is needed to determine whether the revenue justifies logistics expenses. Road transportation accounts for the largest transportation cost, indicating an opportunity to optimize route planning.

**Action:**
- Evaluate Route A's profit contribution rather than focusing solely on revenue.
- Investigate opportunities to reduce road transportation costs through route optimization or carrier negotiations.
- Monitor Carrier B's shipping performance to ensure higher costs correspond to better service levels.

**Inventory**

**Insight:**
Eighty-five products currently require replenishment, indicating potential stockout risks if procurement actions are delayed. Cosmetics products have the highest inventory coverage, which may suggest slower inventory turnover and excess stock.

**Action:**
- Prioritize replenishment orders for products below their reorder points.
- Review procurement schedules for slow-moving products to reduce excess inventory holding costs.

**Quality**

**Insight:**
Supplier 5 consistently records the highest average defect rate, indicating potential quality control issues. Products transported by road also exhibit higher defect rates compared to other transportation modes, suggesting that logistics conditions may be affecting product quality.

**Action:**
- Conduct a supplier quality audit for Supplier 5.
- Review packaging and handling procedures for road transportation.
- Increase inspection frequency for products supplied by high-defect vendors.

---

