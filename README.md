# Supply Chain On-Time Delivery & Revenue Risk Analysis

![Supply Chain Dashboard](dashboard/dashboard_preview.png)

## Project Overview
An end-to-end operational analytics project analyzing **180,000+ global supply chain orders** to identify fulfillment bottlenecks, evaluate shipping mode reliability, and quantify revenue exposed to late deliveries.

**Tech Stack:** Python (Pandas), Power BI (DAX, Power Query), Jupyter Notebook

---

## Key Performance Indicators (KPIs)
* **Total Shipments Analyzed:** [Insert your Total Shipments figure]
* **Overall Late Delivery Risk Rate:** [Insert your % figure, e.g., 54.8%]
* **Total Revenue at Risk (Delayed Orders):** $[Insert your Delayed Revenue figure]

---

## Key Business Insights
1. **Shipping Mode Bottlenecks:** [e.g., *First Class and Second Class shipments experienced disproportionately high delay rates compared to Standard Class, indicating unrealistic SLA promises.*]
2. **Regional Revenue Exposure:** [e.g., *Europe and LATAM accounted for the largest share of delayed order revenue, driven by specific product categories.*]
3. **Seasonal Delivery Trends:** [e.g., *Monthly trend tracking revealed recurring delay spikes during peak Q4 shipping windows.*]

---

## Actionable Recommendations
* **Re-calibrate SLA Promises:** Adjust promised delivery windows for expedited shipping tiers where fulfillment consistently misses targets.
* **Prioritize High-Value Lanes:** Allocate buffer inventory and carrier capacity to top revenue-generating regions with the highest late-delivery rates.

---

## Repository Structure
* `notebooks/supply_chain_eda.ipynb`: Data cleaning, feature engineering (`Shipping_Days`, `Is_Delayed`), and exploratory analysis in Python.
* `dashboard/Supply_Chain_Dashboard.pbix`: Interactive Power BI report with dynamic DAX measures and slicers.
* `data/`: Dataset source documentation and preprocessing notes.
