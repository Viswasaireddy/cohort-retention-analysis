# 🔁 Cohort Retention & Repeat Purchase Analysis

## Problem

Repeat purchase behavior varies significantly across product categories, limiting long-term customer lifetime value (LTV).

## Approach

* Built cohort retention tables using SQL
* Analyzed repeat purchase behavior across lifecycle windows (0–14d, 15–30d, etc.)
* Segmented customers by product category
* Measured LTV and repeat rate relationships

## Key Insights

### Repeat Purchase Rate vs LTV

Higher repeat rates directly correlate with higher LTV
![Chart](fig1_repeat_rate_ltv.png)

### Lifecycle Heatmap (14-Day Windows)

Most repeat activity happens after 30+ days
![Chart](fig2_lifecycle_heatmap.png)

### Cohort Retention Matrix

Retention stabilizes around ~18–20% after Month 1
![Chart](fig3_cohort_matrix.png)

### LTV Opportunity

Major revenue opportunity from improving early repeat purchase
![Chart](fig4_ltv_opportunity.png)

---

## Business Impact

* +10% repeat purchase opportunity
* ₹37.5L potential LTV uplift
* High-value segments: Electronics, Home & Kitchen

---

## Decision

Focus on early lifecycle engagement and reactivation campaigns

---

## Tools

SQL, Python (Pandas, Matplotlib)
