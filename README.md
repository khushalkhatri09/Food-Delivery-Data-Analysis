# Food Delivery Data Analysis

A comprehensive exploratory data analysis (EDA) project evaluating customer buying behavior, delivery logistics, surge pricing dynamics, and revenue trends across 8,000 transactions. Built using Python, Pandas, Matplotlib, and Seaborn.

---

## Project Overview

Online food delivery platforms balance complex operations: fleet allocation, dynamic surge pricing, restaurant onboarding, and customer retention. This project processes transactional delivery records to diagnose logistics bottlenecks, customer satisfaction drivers, and city-level revenue contribution.

### Key Objectives
- Analyze order volume and revenue generation across major metropolitan markets.
- Track hourly and monthly fluctuations to identify demand spikes.
- Assess the operational link between delivery duration and customer review scores.
- Measure the impact of dynamic pricing and discount promotions on average order value (AOV).
- Segment user behavior across first-time vs. returning cohorts.

---

## Tech Stack

- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab

---

## Key Business Insights

1. **City Revenue Driver:** Bengaluru generated the highest gross revenue (~28% of total platform volume), followed closely by Mumbai and Delhi NCR.
2. **Peak Demand Windows:** Intraday demand follows a distinct bimodal distribution peaking during Lunch (12:00–14:00) and Dinner (19:00–21:00).
3. **Category Dominance:** Biryani and Pizza represent over 40% of all ordered items across regions.
4. **Customer Retention:** Returning users account for over 70% of total transactions, reflecting high platform stickiness.
5. **Delivery Impact on Ratings:** Late deliveries heavily penalize customer satisfaction; orders exceeding 45 minutes saw a 4x increase in 1-star ratings compared to sub-30-minute deliveries.
6. **Payment Trends:** UPI dominates checkout preferences (over 55% share), followed by Credit Cards (~22%).
7. **Surge Pricing Elasticity:** Dynamic pricing multipliers of 1.15x–1.35x applied during peak hours yielded a 12.4% increase in average ticket size without suppressing conversion.

---

## How to Run Locally

1. Clone or download the repository files.
2. Install the necessary dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn ipykernel
