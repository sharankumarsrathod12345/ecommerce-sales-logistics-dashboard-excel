
# E-Commerce Sales & Logistics Dashboard

## Project Overview

An interactive Excel dashboard designed to analyze e-commerce performance across sales trends, customer demographics, and shipping logistics. This project transforms raw transaction data into actionable business insights to help stakeholders optimize logistics timelines, identify channel-specific growth opportunities, and track performance targets.

<p align="center">
  <img src="images/dashboard_interaction.gif" max-width="100%" height="auto" alt="Dashboard Preview">
</p>

![Dashboard Preview](images/dashboard_preview.png)


---

## 📊 Analytical Framework

### Core Key Performance Indicators (KPIs) Tracked

| Key Performance Indicator | Current Metric | Performance Status | Business Action Insight |
| :--- | :---: | :---: | :--- |
| 📦 **Total Orders** | 2,400 | 🟢 Stable | Core volume driver meeting standard operational capacity. |
| 🏷️ **Total Quantity** | 11,997 | 🟢 High | Strong item-per-order ratio; inventory rotation is healthy. |
| 💰 **Total Amount** | ₹649.0k | 🟢 On Track | High-performing revenue target driven heavily by California channels. |
| ⭐ **Avg. Rating** | 4.0 / 5.0 | 🟡 Baseline | Solid baseline score; customer service workflows can optimize this further. |
| 🚚 **Avg. Days to Deliver** | 2.3 Days | 🟢 Excellent | Fulfillment cycle is highly efficient across main shipping lanes. |

---

### 📊 Dynamic KPI Capabilities

The dashboard architecture features an automated Key Performance Indicators (KPI) tracking tier. Instead of static snapshots, these monitoring modules are engineered to dynamically process raw, changing transaction rows to empower stakeholders with the following diagnostic features:

* 📦 **Volume & Throughput Monitoring (Total Orders & Quantity):** Continuously tracks real-time transaction density and velocity. This allows operations managers to instantly scale warehousing staff and ensure processing lines match active customer demand profiles.
* 💰 **Revenue Architecture (Total Amount Tracking):** Aggregates cross-platform gross revenue across regional boundaries. This equips financial teams to track sales target margins dynamically and evaluate the instant fiscal health of localized market expansions (e.g., California channels).
* ⭐ **Customer Sentiment Analysis (Average Rating tracking):** Calculates real-time rolling customer satisfaction parameters. This serves as an automated early-warning system, enabling service desks to flag immediate logistics bottlenecks or product quality drop-offs before brand equity is impacted.
* 🚚 **Logistics Turnaround Engine (Avg. Days to Deliver):** Measures pipeline efficiency intervals by continuously tracking fulfillment cycles. This calculation isolates shipping lanes experiencing transit fatigue, helping supply chain managers renegotiate courier contracts or restructure delivery windows.

### 🚨 Automated Alerting Thresholds & Operational Signaling

To prevent information overload, the dashboard integrates automated visual signaling rules. The KPI modules instantly recalculate and change color states based on strict operational data rules, allowing management to manage by exception:

* 🟢 **Target Achieved / Healthy State:** 
  * *Condition:* Orders tracking stable, delivery times $\le$ 2.5 days, or Average Rating $\ge$ 4.0.
  * *Business Signal:* Operations are running smoothly within standard capacity. No immediate tactical action required.
* 🟡 **Warning / Variance Detected:** 
  * *Condition:* Average Rating drops between 3.5 and 3.9, or Delivery Times drift between 2.6 and 3.5 days.
  * *Business Signal:* Early indicator of supply chain friction or localized customer dissatisfaction. Triggers a mandatory review of courier lanes or recent customer feedback logs.
* 🔴 **Critical Action Required:** 
  * *Condition:* Average Rating falls below 3.5, or Delivery Times spike past 3.5 days.
  * *Business Signal:* High-priority operational bottleneck. Automatically signals management to intervene, pause underperforming shipping lanes, or adjust warehouse fulfillment priorities to protect brand equity.

### 🎯 Business Questions Addressed

* **1. Trend in the last 13 weeks:** How is our volume shifting over a rolling fiscal quarter?
* **2. How our customers like to buy:** Which acquisition platforms (App, Website, Instagram) yield the highest conversions?
* **3. How many they buy?:** What is the typical distribution frequency of item counts per transaction order?
* **4. Which products are popular?:** What is the volume performance breakdown of specific apparel items categorized by gender?
* **5. Overall gender split:** What are the broader macro demographic trends across our user base?
* **6. Where do our customers live?:** What does our geographical density map look like for regional distribution strategies?
* **7. How long we take to ship the orders:** What does our absolute logistical operational turnaround look like day-by-day?
* **8. How happy are our customers?:** Are customer satisfaction tiers trending positively over consecutive months?

---

## 💡 Key Business Insights & Strategic Recommendations

* **Sales Dynamics:** Evaluated quantities and total revenue across a rolling 13-week period to identify order volume peaks, allowing supply chain teams to balance inventory.
* **Customer Acquisition:** Uncovered that the App and Instagram platforms are highly effective at capturing the female demographic, pointing to optimal channels for targeted marketing spends.
* **Logistics & Fulfillment:** Analyzed order processing intervals to discover critical delivery delays occurring between days 2 and 4, identifying an opportunity to streamline warehouse transit procedures.

---

## 🛠️ Technical Excel Competencies Demonstrated

* **Advanced Data Modeling:** Implemented relational mapping between primary sales transactions, global geography keys, and shipping tracking fields.
* **Complex Formula Design:** Leveraged analytical functions including `XLOOKUP`, `INDEX/MATCH` matrix structures, and logical nested `IF` chains for clean extract-transform-load (ETL) processing.
* **UI/UX Engineering:** Structured interactive dashboards utilizing synchronized cross-filtering slicers, localized map chart visualizations, and locked sheet structure controls to prevent end-user formatting breaks.
* **Pivot Integration Layer:** Constructed isolated data aggregation matrices to dynamically update front-end visualizations without introducing processing latency.
