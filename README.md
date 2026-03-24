# A/B Testing Intelligence | Advertising Impact Analysis

## Project Overview
This project provides a deep-dive analysis of an A/B testing campaign to determine the effectiveness of display advertisements versus a control group PSA. By processing over 500,000 rows of raw marketing logs, this dashboard identifies key conversion drivers, optimal ad frequency, and high-impact timing for budget allocation.

**Key Achievement:** Identified a **43.09% performance lift** in the treatment group compared to the baseline.

---

## 🛠️ Technical Stack & Workflow
* **Data Preparation (Excel):** * Performed data cleaning and deduplication.
    * Engineered new metrics including `Boolean to Integer` conversion for success tracking.
    * Created custom `Time-of-Day` and `Ad-Impression` bins for granular analysis.
* **Business Intelligence (Power BI):**
    * Developed complex DAX measures for **Conversion Rate (CR)** and **Campaign Lift**.
    * Designed a high-fidelity "Premium Business" themed dashboard (Brown/Gold palette).
    * Implemented interactive slicers for segment-based deep dives.

---

## Key Insights & Recommendations

### 1. Performance Lift
The **Ad Group** achieved a **2.55% CR** against the **1.79% Baseline (PSA)**. This statistically significant lift validates the current creative strategy.

### 2. The "Golden Window"
Conversion velocity peaks on **Monday Afternoons**. Recommendation: Reallocate 15-20% of underperforming weekend budgets to this high-intent window.

### 3. Ad Saturation & Frequency
Using the **Ad Frequency Response Curve**, I identified a saturation point at **100 impressions**. 
* **Action:** Implement a frequency cap at 100 ads/user to prevent "Ad Fatigue" and reduce wasted spend.

---

## How to Use This Dashboard
1.  **Executive View:** Check the top KPI cards for immediate campaign health.
2.  **Segment Analysis:** Use the **Test Group** slicer to compare "Ad" vs "PSA" behavior across all visuals.
3.  **Efficiency Check:** Analyze the **Ad Saturation Curve** to determine the point of diminishing returns for your specific ad spend.

---
