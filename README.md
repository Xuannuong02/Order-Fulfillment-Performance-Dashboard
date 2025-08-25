# Order Fulfillment Performance Dashboard

## 📊 Project: Order Fulfillment Performance Dashboard
## 🏢 Domain: Retail / FMCG – Order & Sales Monitoring
## 🛠 Tools: Power BI, DAX, Data Modeling

### 1. Business Problem

Order fulfillment is a key KPI for retailers. Incomplete (partial) and cancelled orders directly impact revenue, operations, and customer satisfaction. Management required a centralized dashboard to:

Monitor In Full vs Partial vs Cancelled Orders.

Track order quantity and revenue impact.

Identify top customers, channels, and cancellation reasons.

Enable MTD and YTD comparisons.

### 2. Data Sources & Modeling

Sales Orders Table: order ID, customer, status, amount, channel, warehouse.

Customer & Group Tables: customer hierarchy, group name.

Calendar Table: for time intelligence (YTD, MTD).

Reference Tables: cancellation reasons, brand, region.

👉 Built a star schema model in Power BI linking facts (orders) with dimensions (customer, date, channel).

### 3. Dashboard Design

The solution includes three integrated dashboards with filters:

🔹 In Full Orders Overview

KPIs: Total orders, In Full Orders, Fulfillment Rate (%).

Trend: Orders vs In Full orders by month.

Breakdown: By channel, customer group, region.

Customer detail: Current vs previous month comparison.

🔹 Partial Orders Overview

KPIs: Total Partial Orders, % Rate.

Trend: Partial orders over months.

Breakdown: By channel.

Top 5 customer groups with partial orders.

Drilldown: Customer-level analysis.

🔹 Cancelled Orders Overview

KPIs: Cancelled orders (quantity & amount), % cancellation rate.

Trend: Cancelled orders by month.

Breakdown: By channel.

Top 5 cancellation reasons.

Drilldown: Cancelled orders by customer.

### 4. Key Insights

Fulfillment Rate: Only 68.65% (quantity) and 60.47% (value) delivered in full (Aug).

Partial Orders: 30% of orders were partially fulfilled, mostly from WIN group (25.8K).

Cancelled Orders: 1.04% of total, with major reasons being No Reason & stock issues.

Channel View: CVS channel had the highest In Full Orders; GT had the most cancellations.

Customer View: WIN was the top performer in full orders but also high in partial → risk factor.

### 5. Impact

End-to-end visibility of fulfillment performance (Full, Partial, Cancelled).

Ability to track missed revenue opportunities.

Identified root causes by channel, customer, and cancellation reason.

Supported better decisions for supply chain, sales, and account management.

✅ Outcome: Improved order monitoring, proactive actions to reduce partial/cancelled orders, revenue protection, and higher customer satisfaction.
