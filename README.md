# Order Status Analysis Dashboard
## 📊 Project: Order Status Analysis Dashboard
## 🏢 Domain: Retail / FMCG – Order & Sales Monitoring
## 🛠 Tools: Power BI, DAX, Data Modeling
### 1. Business Problem

Order fulfillment is a key KPI for retailers. Incomplete (partial) and cancelled orders directly impact revenue, operations, and customer satisfaction. Management required a centralized dashboard to:

Monitor In Full vs Partial vs Cancelled Orders

Track order quantity and revenue impact

Identify top customers, channels, and cancellation reasons

Enable MTD and YTD comparisons

### 2. Data Sources & Modeling

Sales Orders Table: order ID, customer, status, amount, channel, warehouse

Customer & Group Tables: customer hierarchy, group name

Calendar Table: for time intelligence (YTD, MTD)

Reference Tables: cancellation reasons, brand, region

👉 Built a star schema model in Power BI linking facts (orders) with dimensions (customer, date, channel) for efficient filtering and analytics.

### 3. Dashboard Design

The solution includes three integrated dashboards with interactive filters:

🔹 In Full Orders Overview

KPIs: Total orders, In Full Orders, Fulfillment Rate (%)

Trend: Orders vs In Full Orders by month

Breakdown: By channel, customer group, and region

Customer Detail: Current vs previous month comparison

🔹 Partial Orders Overview

KPIs: Total Partial Orders, Partial Order Rate (%)

Trend: Partial orders over months

Breakdown: By channel

Top 5 Customer Groups: with highest partial orders

Drilldown: Customer-level analysis for deeper insights

🔹 Cancelled Orders Overview

KPIs: Cancelled orders (quantity & amount), Cancellation Rate (%)

Trend: Cancelled orders by month

Breakdown: By channel

Top 5 Cancellation Reasons

Drilldown: Cancelled orders by customer

### 4. Key Insights

Fulfillment Rate: Only 68.65% (quantity) and 60.47% (value) delivered in full (Aug)

Partial Orders: 30% of orders were partially fulfilled, mostly from WIN group (25.8K orders)

Cancelled Orders: 1.04% of total, with major reasons being No Reason & Stock Issues

Channel View: CVS channel had the highest In Full Orders; GT had the most cancellations

Customer View: WIN was the top performer in full orders but also high in partial → risk factor

### 5. Impact

Provides end-to-end visibility of fulfillment performance (Full, Partial, Cancelled)

Enables tracking of missed revenue opportunities

Identifies root causes by channel, customer, and cancellation reason

Supports better decision-making for supply chain, sales, and account management

✅ Outcome: Improved order monitoring, proactive actions to reduce partial/cancelled orders, protect revenue, and increase customer satisfaction

### 6. Additional Highlights (Optional)

Interactive Filters: Channel, Customer Group, Region, Time Period

Comparison Views: Month-over-Month (MoM) & Year-over-Year (YoY)

Drillthrough Functionality: From KPIs to order-level details for actionability

Conditional Formatting: Highlights critical areas needing attention
###Image
<img width="837" height="765" alt="image" src="https://github.com/user-attachments/assets/b164663b-e3e9-4166-b92a-7bc0b633a76f" />
<img width="817" height="768" alt="image" src="https://github.com/user-attachments/assets/39ded47a-f53a-4940-9464-641f9a2504b6" />
<img width="824" height="771" alt="image" src="https://github.com/user-attachments/assets/e6bd16eb-6150-4c7b-b295-3375158345e1" />


